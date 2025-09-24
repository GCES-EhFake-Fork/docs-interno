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

- [ ] Entender melhor o guia de Contribuição
- [ ] Propor com a equipe o início da raspagem de algum portal
- [ ] Reunir e alinhas os objetivos com a equipe

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
