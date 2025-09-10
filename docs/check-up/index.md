# Check-up

## O que é o Check-up?

O **Check-up** é uma ferramenta avançada de **extração automatizada de conteúdo jornalístico** desenvolvida pela comunidade **EH-FAKE** para combater a desinformação no cenário digital brasileiro. Este projeto representa uma evolução significativa de uma solução originalmente criada pelo [**Aos Fatos**](https://aosfatos.org), uma das principais organizações de fact-checking do Brasil.

## 🎯 Propósito e Missão

Em um mundo onde a desinformação se espalha rapidamente através das redes sociais e portais de notícias, o Check-up surge como uma resposta tecnológica para **democratizar o acesso à informação jornalística de qualidade** e facilitar a **análise sistemática de conteúdo noticioso**.

O projeto tem como missão principal:

- **Coletar automaticamente** notícias de múltiplos portais brasileiros
- **Extrair e estruturar** o conteúdo completo das matérias jornalísticas
- **Disponibilizar dados organizados** para análise de padrões informativos
- **Facilitar a identificação** de possíveis casos de desinformação
- **Apoiar pesquisadores e fact-checkers** com dados estruturados e acessíveis

## 🔄 Evolução do Projeto

### Origem: Aos Fatos

O Check-up nasceu como uma adaptação de uma ferramenta desenvolvida pela organização **Aos Fatos**, reconhecida nacionalmente por seu trabalho de verificação de fatos e combate às fake news.

### Transformação pela EH-FAKE

A comunidade **EH-FAKE** reimaginou e expandiu significativamente o escopo da ferramenta:

- **Antes**: Focava na análise de anúncios publicitários para identificar propagandas enganosas
- **Agora**: Concentra-se na extração completa de conteúdo jornalístico para análise abrangente de desinformação

## 🏗️ Como Funciona

O Check-up opera através de uma **arquitetura de duas camadas** que trabalham em sinergia:

### 1. Camada de Coleta (Spiders)

Utiliza **web crawlers** inteligentes baseados na biblioteca Scrapy para:

- Navegar automaticamente nas páginas iniciais dos portais de notícias
- Identificar e coletar URLs de artigos jornalísticos
- Filtrar conteúdo relevante, ignorando seções como entretenimento ou publicidade
- Armazenar sistematicamente as URLs coletadas em banco de dados

### 2. Camada de Extração (Plays)

Emprega **web scrapers** sofisticados utilizando Playwright para:

- Acessar individualmente cada URL coletada
- Simular navegação humana para contornar proteções anti-bot
- Extrair conteúdo estruturado de cada notícia
- Organizar e armazenar dados em formato padronizado

## 📊 Dados Extraídos

Para cada notícia processada, o sistema captura:

- **📰 Título**: Manchete principal da matéria
- **📝 Descrição**: Subtítulo, linha fina ou resumo editorial
- **📖 Corpo**: Texto completo da reportagem
- **🏷️ Tags**: Categorias, assuntos e etiquetas de classificação
- **🌐 Metadados**: Portal de origem, data de coleta, URL original

## 🎯 Portais Monitorados

O projeto atualmente monitora **8 portais brasileiros** principais:

### Totalmente Funcionais:

- **Metrópoles** - Portal de notícias do Distrito Federal
- **IG** - Portal de notícias generalistas
- **MaisGoiás** - Notícias regionais de Goiás
- **AliadosBrasil** - Portal de notícias políticas
- **Veja** - Revista semanal de informação
- **R7** - Portal de notícias da Record
- **UOL** - Universo Online, um dos maiores portais do Brasil
- **Folha** - Folha de S.Paulo, jornal de referência nacional

### Em Desenvolvimento:

- Estadão, Globo, RBS, Terra (em fase de implementação)

## 🛠️ Tecnologias Utilizadas

O Check-up é construído com tecnologias modernas e robustas:

- **Backend**: Python com FastAPI
- **Frontend**: React com Vite
- **Banco de Dados**: PostgreSQL
- **Armazenamento**: MinIO (S3-compatible)
- **Web Scraping**: Scrapy + Playwright
- **Containerização**: Docker e Docker Compose
- **Automação**: Makefile para workflows

## 🌟 Diferenciais do Projeto

### Escalabilidade

- Arquitetura preparada para adicionar novos portais facilmente
- Sistema de filas para processamento eficiente
- Infraestrutura containerizada para deploy flexível

### Robustez

- Tratamento inteligente de erros e timeouts
- Sistema de retry automático
- Logs detalhados para monitoramento

### Acessibilidade

- Interface web intuitiva para visualização
- API REST para integração com outras ferramentas
- Documentação completa para desenvolvedores

## 🎓 Impacto Educacional e Social

O Check-up não é apenas uma ferramenta técnica, mas um **instrumento de democratização da informação** que:

- **Facilita pesquisas acadêmicas** sobre padrões jornalísticos
- **Apoia organizações de fact-checking** com dados estruturados
- **Promove transparência** no ecossistema informativo brasileiro
- **Educa desenvolvedores** sobre técnicas avançadas de web scraping
- **Fomenta colaboração** entre comunidades tech e jornalismo

## 🚀 Futuro do Projeto

A comunidade EH-FAKE continua expandindo o Check-up com planos para:

- Integração com mais portais regionais e nacionais
- Implementação de análise de sentimentos
- Desenvolvimento de dashboards de análise
- Criação de APIs públicas para pesquisadores
- Estabelecimento de parcerias com organizações de mídia

---

O **Check-up** representa um exemplo concreto de como a tecnologia pode ser utilizada para fortalecer a democracia e combater a desinformação, fornecendo ferramentas acessíveis e transparentes para quem busca compreender melhor o panorama informativo brasileiro.
