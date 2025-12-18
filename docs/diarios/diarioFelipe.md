# Diário de Bordo – Felipe de Sousa Coelho

**Disciplina:** Gerência de Configuração e Evolução de Software
**Equipe:** WebScrapping
**Comunidade/Projeto de Software Livre:** Check-up

---

## Sprint 0 – 02/09/2025 - 10/09/2025

### Resumo da Sprint

Organização do Grupo em subgrupos (Web-Scrapping e IA) e ambientação com o projeto

### Atividades Realizadas

| Data  | Atividade                                    | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                                                                                                         | Status    |
| ----- | -------------------------------------------- | --------------------------------- | ----------------------------------------------------------------------------------------------------------------------- | --------- |
| 08/09 | Leitura da Documentação do projeto Base      | Estudo/Ambientação                | [Docs](https://eh-fake.github.io/docs/land/index.html)                                                                  | Concluído |
| 08/09 | Leitura do `README.md` do Projeto Base       | Estudo/Ambientação                | [README](https://github.com/EH-FAKE/check-up/blob/develop/README.md)                                                    | Concluído |
| 09/09 | Configuração do Ambiente Local               | Configuração                      |                                                                                                                         | Concluído |
| 09/09 | Clonagem do Fork do Repositório              | Configuração                      | [Repositório](https://github.com/GCES-EhFake-Fork/checkUp)                                                              | Concluído |
| 09/09 | Execução de comandos de scrapping para teste | Configuração                      | [Repositório](https://github.com/GCES-EhFake-Fork/checkUp)                                                              | Concluído |
| 10/09 | Documentação do Diário de Bordo              | Doc                               | [Documento](https://github.com/GCES-EhFake-Fork/docs-interno/blob/main/docs/grupo-webscrapping/sprint0/diarioFelipe.md) | Concluído |

### Maiores Avanços

- Entendi a stack do projeto
- Ambientei minha máquina ao repositório
- Rodei alguns scripts prontos
- Estudei como evoluir o software para outros portais de notícia

### Maiores Dificuldades

- Me ambientar com o projeto, com seus repositórios e atividades
- Organizar as entregas com a equipe

### Aprendizados

- Fluxo de execução do projeto
- Ambientar a máquina ao sistema em diferentes SOs (Windows, Linux e macOs)
- Como são guardadas e extraídas informações da base de dados

### Plano Pessoal para a Próxima Sprint

- [x] Entender melhor o guia de Contribuição
- [x] Propor com a equipe o início da raspagem de algum portal
- [x] Reunir e alinhas os objetivos com a equipe

## Sprint 1 – 15/09 - 24/09

### Resumo da Sprint

Foco em criar os scrapers dos portais Brasil de Fato e Agência Pública para coletar notícias de forma consistente e integrar essas mudanças ao fluxo do projeto, com abertura de PRs no repositório base.

### Atividades Realizadas

| Data       | Atividade                                                                            | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                                                                                               | Status    |
| ---------- | ------------------------------------------------------------------------------------ | --------------------------------- | ------------------------------------------------------------------------------------------------------------- | --------- |
| 18/09/2025 | Análise dos scrapers e mapeamento dos portais                                        | Estudo                            | –                                                                                                             | Concluído |
| 24/09/2025 | Início da codificação local do Scrapper dos portais Brasil de Fato e Agência Pública | Código                            | -                                                                                                             | Concluído |
| 24/09/2025 | Criação dos PRs de draft da implementação dos scrapers                               | Código                            | [PR#39](https://github.com/EH-FAKE/check-up/pull/39)<br> [PR#40](https://github.com/EH-FAKE/check-up/pull/40) | Concluído |
| 24/09/2025 | Criação do Relatório da Sprint 1                                                     | Doc                               | [PR#41](https://github.com/GCES-EhFake-Fork/docs-interno/pull/41)                                             | Concluído |

### Maiores Avanços

- Melhor entendimento do padrão de normalização de notícias do projeto.
- Scrapers dos Portais Brasil de Fato e Agência Pública em estado de rascunho.
- PRs abertos para revisão e feedback da equipe e mantenedores.

### Maiores Dificuldades

- Garantir consistência dos campos (título, descrição, conteúdo e tags).
- Adequar a carga horaria para desenvolvimento e testes.

### Aprendizados

- Convenções do projeto para saída de dados e organização dos scrapers.
- Estratégias para tornar seletores mais robustos a mudanças de HTML.

### Plano Pessoal para a Próxima Sprint

- [ ] Acompanhar e endereçar feedbacks até o merge dos PRs (#39 e #40).
- [ ] Avaliar e iniciar contribuição em um próximo portal.

## Sprint 2 – 25/09 - 08/09

### Resumo da Sprint

Foquei nessa sprint em melhorar ainda mais a estrututra do projeto e organização , alguns testes de comunicação entre o front e back da aplicação e implementar algumas ideias de melhora no front

### Atividades Realizadas

| Data  | Atividade                                          | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                                              | Status    |
| ----- | -------------------------------------------------- | --------------------------------- | ------------------------------------------------------------ | --------- |
| 22/09 | Implementação do Scrapper do portal Brasil de Fato | Implementação                     | -                                                            | Concluído |
| 24/09 | Testes e adequação de CI                           | Documentação e Teste              | [PR#16](https://github.com/GCES-EhFake-Fork/checkUp/pull/16) | Concluído |
| 08/10 | Criação do Relatório da Sprint 12                  | Documentação                      | -                                                            | Concluído |

### Maiores Avanços

- Scrapers do Portal Brasil de Fato completo.
- PRs abertos para revisão e feedback da equipe e mantenedores.

### Maiores Dificuldades

- Criar e adequar scrapper ao portal
- Adequar a carga horaria para desenvolvimento e testes.

### Aprendizados

- Como fazer o scrapper passo-a-passo

### Plano Pessoal para a Próxima Sprint

- [x] Acompanhar e endereçar feedbacks até o merge dos PRs (#39 e #16).
- [ ] Avaliar e iniciar contribuição em um próximo portal.

## Sprint 3 – 09/10/2025 - 22/10/2025

### Resumo da Sprint

A Sprint 3 teve como foco principal a **documentação do framework de testes automatizados do projeto Check-up**, consolidando o estado atual da cobertura de testes, sua estrutura, ferramentas utilizadas e integração com o pipeline de CI/CD.
O objetivo foi tornar o ambiente de testes mais compreensível e acessível à equipe, padronizando processos e registrando todas as dependências, estratégias e convenções utilizadas.
Essa entrega fortalece a base de qualidade do projeto, facilitando futuras contribuições e manutenção do sistema de testes.

### Atividades Realizadas

| Data       | Atividade                                                                                  | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                                                   | Status    |
| ---------- | ------------------------------------------------------------------------------------------ | --------------------------------- | ----------------------------------------------------------------- | --------- |
| 20/10/2025 | Criação de uma documentação descrevendo o estado atual dos testes                          | Documentação                      | [PR#23](https://github.com/GCES-EhFake-Fork/checkUp/pull/23)      | Concluído |
| 20/10/2025 | Criação de uma Issue de implementação de melhorias na área de testes                       | Documentação                      | [Issue#22](https://github.com/GCES-EhFake-Fork/checkUp/issues/22) | Concluído |
| 22/10/2025 | Revisão do [PR#39](https://github.com/EH-FAKE/check-up/pull/39) e adição das contribuições | Discussão/Documentação            | [PR#23](https://github.com/GCES-EhFake-Fork/checkUp/pull/23)      | Concluído |

### Maiores Avanços

- **Documentação centralizada e completa**: Criação de um documento abrangente descrevendo a estrutura dos testes, dependências, estratégias e integração com CI/CD;
- **Mapeamento da cobertura de testes**: Identificação dos módulos testados (como `BasePlay` e `UOLPlay`), quantificação de métodos e avaliação de lacunas de cobertura;
- **Padronização de convenções**: Definição clara de padrões de nomenclatura, organização de diretórios e boas práticas para criação de novos testes;
- **Integração ao fluxo de desenvolvimento**: Consolidação da execução de testes dentro do pipeline automatizado, garantindo execução contínua;
- **Colaboração ativa na revisão**: Participação direta na revisão cruzada de PRs e integração de contribuições de outros membros da equipe.

### Maiores Dificuldades

- **Curadoria de informações**: Reunir e consolidar dados dispersos sobre os testes exigiu leitura detalhada de múltiplos arquivos e históricos de PRs;
- **Atualização de referências**: Garantir que todos os exemplos de código, versões de dependências e links estivessem atualizados e coerentes;
- **Alinhamento entre repositórios**: Ajustar referências e links para refletir corretamente as diferenças entre forks e o repositório principal;
- **Equilíbrio entre detalhe e clareza**: Redigir uma documentação técnica extensa sem comprometer a legibilidade e objetividade.

### Aprendizados

- **Boas práticas de documentação técnica**: Aprofundamento na escrita de documentação de testes de software voltada para equipes colaborativas;
- **Compreensão do ecossistema de testes**: Entendimento mais sólido sobre a integração entre pytest, Docker, banco de dados e CI/CD;
- **Colaboração assíncrona**: Desenvolvimento de habilidades de comunicação e revisão em PRs colaborativos e cross-repo;
- **Padronização de testes**: Importância de manter consistência entre nomes, estrutura e convenções para facilitar manutenção futura.

### Plano Pessoal para a Próxima Sprint

- [ ] Acompanhar reviews do [PR#39](https://github.com/EH-FAKE/check-up/pull/39) até o merge na branch principal
- [ ] Implementar melhorias descritas e finalizar a [Issue#22](https://github.com/GCES-EhFake-Fork/checkUp/issues/22)

## Sprint 4 – 23/10/2025 - 18/11/2025

### Resumo da Sprint

Foco em acompanhar a evolução e refinamentos do **PR#39** (scraper Brasil de Fato / Agência Pública), consolidar o plano de melhorias da área de testes (Issue#22) e iniciar a implementação prática de casos de teste automatizados para scrapers (normalização e campos obrigatórios). Também estrutura inicial para futuras métricas de cobertura de testes no pipeline.

### Atividades Realizadas

| Data       | Atividade                                                               | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                                                   | Status       |
| ---------- | ----------------------------------------------------------------------- | --------------------------------- | ----------------------------------------------------------------- | ------------ |
| 23/10/2025 | Acompanhamento contínuo e revisão incremental do PR de scrapers (PR#39) | Discussão/Documentação            | [PR#39](https://github.com/EH-FAKE/check-up/pull/39)              | Em andamento |
| 23/10/2025 | Revisão incremental dos PRs de scrapers (PR#80, PR#81).                 | Revisao                           | [PR#80](https://github.com/EH-FAKE/check-up/pull/80), [PR#81](https://github.com/EH-FAKE/check-up/pull/81)             | Concluido | 
| 12/11/2025 | Estudo de gaps de cobertura e requisitos de testes                      | Estudo                            | [Issue#22](https://github.com/GCES-EhFake-Fork/checkUp/issues/22) | Concluído    |
| 18/11/2025 | Início da implementação de testes automatizados para scrapers           | Código                            | -                                                                 | Concluído    |

### Maiores Avanços

- Acompanhamento ativo do PR#39, contribuindo com revisões e sugestões para estabilização dos scrapers.
- Mapeamento detalhado dos gaps de cobertura de testes, com definição clara de critérios para novos casos.
- Início da implementação de testes automatizados focados em normalização e campos obrigatórios dos scrapers.

### Maiores Dificuldades

- Balancear o tempo entre revisão de PRs e desenvolvimento de novos testes.
- Definir critérios objetivos para casos de teste em scrapers com diferentes estruturas HTML.

### Aprendizados

- Entendimento da inserção de scrapers na arquitetura geral do projeto.

### Plano Pessoal para a Próxima Sprint

- [x] Acompanhar reviews do [PR#39](https://github.com/EH-FAKE/check-up/pull/39) até o merge na branch principal
- [ ] Continuar implementação de casos de teste automatizados para scrapers
