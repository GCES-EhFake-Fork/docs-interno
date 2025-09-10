# Políticas da comunidade

## Governança

A comunidade **EH FAKE** possui uma estrutura de governança simplificada, com um único mantenedor principal:

**🔧 Mantenedor Principal:**

- **Leonardo Lago Moreno** ([lelamo2002](https://github.com/lelamo2002))

### Estrutura de Governança

Atualmente, **não há papéis formalmente definidos** na governança da comunidade. O projeto adota um modelo colaborativo onde:

- O mantenedor principal possui responsabilidades de supervisão geral
- Os membros contribuidores agora terão **acesso direto ao repositório base** (sem necessidade de fork para contribuições)
- Decisões técnicas são tomadas de forma colaborativa através de discussões em issues e pull requests
- A comunidade está em processo de crescimento e formalização de estruturas organizacionais

### Organização do Código

![arquitetura do projeto](https://eh-fake.github.io/docs/assets/diagrama-pipeline.png)

- **Spiders**: Web Crawlers que coletam as URL's de artigos/notícias presentes em sites de notícias e guardam esses links no banco de dados.

- **Plays**: Web Scrappers que acessam as URL's coletadas pelas Spiders e extraem o conteúdo da página.

- **Estruturação dos dados**: O conteúdo da página extraído é armazenado de forma estruturada utilizando PostgreSQL.

  - MinIO: Armazenamento de screenshots e arquivos de mídia obtidos no scrapping (descontinuado)

- **API REST**: Fornece os dados coletados por meio de requisições HTTP

- **Interface web**: Visualização dos dados em uma página web.

**ESTRUTURA DE PASTAS**

```text
check-up/
├── plays/       # Lógicas específicas de coleta
├── spiders/     # Crawlers (spiders)
├── tests/       # Testes com Pytest
├── utils/       # Funções utilitárias
├── web/
│   ├── server/  # Backend FastAPI
│   └── client/  # Frontend React
└── Makefile     # Scripts de automação
```

### Fluxo de Contribuição

O projeto CheckUp adota um modelo de contribuição baseado em issues estruturadas e pull requests. O processo é dividido em etapas bem definidas para garantir qualidade e consistência:

#### 1. Abertura de Issue

Toda contribuição deve começar com a **abertura de uma issue** utilizando um dos templates padronizados disponibilizados pela comunidade:

- **🆕 Novo Scraper de Portal**: Para criação de scrapers completamente novos
- **🔧 Adaptar Scraper Existente**: Para adaptação de scrapers já existentes
- **🐛 Correção de Bug**: Para reportar e corrigir problemas identificados

Cada template possui campos específicos que devem ser preenchidos, incluindo informações técnicas sobre o portal, URLs de teste e critérios de aceitação detalhados.

#### 2. Fork e Clone do Projeto

Após a criação da issue, o contribuidor deve:

1. **Forkar o repositório** para sua conta pessoal no GitHub
2. **Clonar o fork** para sua máquina local de desenvolvimento
3. Criar uma **branch específica** para a funcionalidade/correção

#### 3. Desenvolvimento e Implementação

O contribuidor irá codificar a funcionalidade seguindo os padrões estabelecidos:

- **Para novos scrapers**: Implementar tanto o Spider (coleta de URLs) quanto o Play (extração de conteúdo)
- **Para adaptações**: Atualizar seletores e remover funcionalidades obsoletas
- **Para correções**: Identificar e resolver o problema reportado

#### 4. Testes e Validação

Antes de submeter a contribuição, é obrigatório testar a funcionalidade contra os **critérios de aceitação** definidos na issue original.

#### 5. Pull Request

Após validação local, o contribuidor deve abrir uma **Pull Request (PR)** para o repositório base, que será analisada pelos mantenedores do projeto.

### Critérios de Aceitação

Os critérios de aceitação variam conforme o tipo de contribuição:

#### Para Novos Scrapers:

- **Extração Completa**: Deve extrair obrigatoriamente 4 campos:

  - Título da notícia
  - Descrição/subtítulo (quando disponível)
  - Corpo completo do texto
  - Tags/categorias associadas

- **Estrutura Técnica**:

  - Spider herda de `BaseSpider` e implementa filtragem adequada via `allow_url()`
  - Play herda de `BasePlay` e implementa método `match()`
  - Coleta apenas URLs da página inicial (sem crawling recursivo)
  - Retorna `EntryItem` com todos os campos preenchidos

- **Validação**:
  - Testado com 5-10 URLs reais fornecidas na issue
  - Pipeline completo funcional (`make crawl_[nome]` + `make scrape_[nome]`)
  - Dados salvos corretamente no PostgreSQL
  - Ausência de erros críticos nos logs

#### Para Adaptações de Scrapers Existentes:

- **Atualização de Seletores**: Re-inspeção do portal e atualização de seletores CSS/XPath
- **Remoção de Código Obsoleto**: Eliminação de funcionalidades descontinuadas (ex: screenshots)
- **Implementação de Novos Campos**: Adição de extração de descrição e tags
- **Filtragem Aprimorada**: Garantia de coleta apenas de URLs de notícias válidas

#### Para Correções de Bug:

- **Reprodução do Problema**: Demonstração clara do bug identificado
- **Solução Efetiva**: Correção que resolve o problema sem introduzir regressões
- **Testes de Validação**: Verificação de que a correção funciona nos cenários reportados

## Qualidade

A comunidade CheckUp mantém rigorosos padrões de qualidade através de políticas bem definidas para código, testes e integração contínua.

### Padrões de Código

#### Convenção de Branches

O projeto adota o **Git Flow** como modelo de ramificação, garantindo entregas organizadas e releases controladas:

- **`main`**: Código estável em produção
- **`develop`**: Integração contínua de funcionalidades
- **`feature/*`**: Desenvolvimento de novas funcionalidades (`feature/<issue>-<slug>`)
- **`bugfix/*`**: Correções durante desenvolvimento (`bugfix/<issue>-<slug>`)
- **`release/*`**: Preparação de versões (`release/vX.Y.Z`)
- **`hotfix/*`**: Correções críticas em produção (`hotfix/vX.Y.Z`)

#### Convenção de Commits

Baseada na especificação **Conventional Commits v1.0.0**, seguindo o padrão:

```
<tipo>(<escopo opcional>): <título no imperativo>

<corpo explicativo opcional>

<rodapé com BREAKING CHANGE e/ou referências de issue>
```

**Tipos de commit permitidos:**

- `feat`: Nova funcionalidade
- `fix`: Correção de bugs
- `docs`: Atualizações de documentação
- `style`: Formatação e estilo de código
- `refactor`: Refatorações sem mudança de comportamento
- `test`: Criação ou modificação de testes
- `perf`: Melhorias de performance
- `build`: Mudanças no sistema de build
- `ci/cd`: Configurações de integração/entrega contínua

#### Lint e Formatação

- **Python**: Flake8 com configurações específicas para o projeto
- **Frontend**: Biome para linting e formatação automática
- **Linha máxima**: 150 caracteres
- **Validação automática** em todos os Pull Requests

### Implementação de Testes

#### Estrutura de Testes

```text
tests/
├── __init__.py
├── plays/
│   ├── __init__.py
│   ├── test_base.py      # Testes para classe base
│   └── test_uol.py       # Testes específicos por portal
└── [outros módulos de teste]
```

#### Tipos de Testes Implementados

**1. Testes Unitários (Pytest)**

- Validação de extração de conteúdo por portal
- Testes de filtragem de URLs
- Verificação de seletores CSS/XPath
- Validação de dados extraídos (título, descrição, corpo, tags)

**2. Testes de Integração**

- Pipeline completo: Spider → Play → Banco de dados
- Conectividade com PostgreSQL e MinIO
- Validação de comandos Makefile

**3. Testes End-to-End (Playwright)**

- Simulação de navegação real nos portais
- Testes com browsers automatizados (Firefox)
- Validação de JavaScript e conteúdo dinâmico

#### Critérios de Qualidade para Testes

- **Cobertura mínima**: Todos os novos scrapers devem incluir testes
- **URLs reais**: Testes devem usar URLs fornecidas nas issues
- **Validação dos 4 campos**: Título, descrição, corpo e tags
- **Testes de regressão**: Garantir que adaptações não quebrem funcionalidades existentes

### Ferramentas de CI/CD

#### Pipeline de Integração Contínua

O projeto utiliza **GitHub Actions** com workflow automatizado executado em:

- Push para branches `main` e `develop`
- Abertura de Pull Requests

#### Jobs do Pipeline

**1. Lint (Python)**

```yaml
- Flake8 para verificação de código Python
- Validação de erros críticos (E9, F63, F7, F82)
- Verificação de complexidade e comprimento de linha
```

**2. Backend (FastAPI)**

```yaml
- Lint específico do backend
- Healthcheck do servidor Uvicorn
- Validação de endpoints (/ping)
```

**3. Frontend (React + Vite)**

```yaml
- Setup Node.js 20 com pnpm
- Lint com Biome
- Build de produção
```

**4. Testes Docker**

```yaml
- PostgreSQL 16 para testes de banco
- MinIO para armazenamento (descontinuado mas mantido para compatibilidade)
- Playwright com Firefox para testes E2E
- Execução completa da suite de testes
```

**5. Build Docker**

```yaml
- Validação de build da imagem Docker
- Cache otimizado com GitHub Actions
- Teste de execução da imagem
```

#### Validações Obrigatórias

Todos os Pull Requests devem:

- ✅ Passar em todos os jobs de CI
- ✅ Ter pelo menos 1 reviewer aprovado
- ✅ Seguir convenções de branch e commit
- ✅ Incluir testes para novas funcionalidades
- ✅ Manter compatibilidade com versões existentes

#### Estratégias de Merge

- **Squash & Merge**: Para `feature/*`, `bugfix/*` e `doc/*`
- **Merge commit**: Para `release/*` e `hotfix/*` (preservando histórico de versionamento)
- **Tags automáticas**: Aplicadas na branch `main` seguindo Semantic Versioning

### Monitoramento de Qualidade

#### Métricas Acompanhadas

- **Taxa de sucesso do CI**: Percentual de builds bem-sucedidos
- **Tempo de execução**: Otimização contínua do pipeline
- **Cobertura de testes**: Especialmente para novos scrapers
- **Regressões**: Detecção precoce de quebras em scrapers existentes

#### Ferramentas de Apoio

- **GitHub Actions**: Automação de CI/CD
- **Pytest**: Framework de testes Python
- **Playwright**: Testes automatizados de browser
- **Docker**: Containerização e testes de ambiente
- **PostgreSQL**: Validação de persistência de dados

## Contato

### Documentação

A documentação completa do projeto CheckUp e demais projetos da organização pode ser encontrada em:

**🔗 [https://eh-fake.github.io/docs/land/index.html](https://eh-fake.github.io/docs/land/index.html)**

#### Issues e Discussões

O principal canal de comunicação da comunidade é através das **Issues do GitHub**, onde:

- ✅ Reportar bugs utilizando templates específicos
- ✅ Solicitar novas funcionalidades
- ✅ Propor melhorias e adaptações
- ✅ Esclarecer dúvidas técnicas
- ✅ Participar de discussões sobre o projeto

#### Para Novos Contribuidores

1. **Consulte a documentação** oficial antes de iniciar
2. **Leia os tutoriais** específicos para seu tipo de contribuição
3. **Abra uma issue** seguindo os templates disponíveis
4. **Participe das discussões** em Pull Requests existentes para aprender

#### Para Questões Técnicas

- **Problemas com scrapers**: Consulte exemplos existentes (`gazetaDoPovo.py`, `metropoles.py`)
- **Dúvidas sobre implementação**: Verifique a documentação das classes base (`BaseSpider`, `BasePlay`)
- **Erros de setup**: Consulte os tutoriais de instalação e configuração

### Links Úteis

- **Documentação Principal**: https://eh-fake.github.io/docs/land/index.html
- **Repositório CheckUp**: [Link do repositório principal]
- **Templates de Issues**: Disponíveis no repositório GitHub
- **Tutoriais Específicos**:
  - `TUTORIAL_CRIACAO_DO_ZERO.md`
  - `TUTORIAL_SPIDERS_PLAYS.md`
