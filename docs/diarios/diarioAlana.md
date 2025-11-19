# Diário de Bordo – Alana Gabriele

**Disciplina:** Gerência e Configuração de Software

**Equipe:** WebScrapping

**Comunidade/Projeto de Software Livre:** Check-up

---

## Sprint 0 – 02/09 - 10/09

### Resumo da Sprint

Esta sprint foi dedicada à ambientação no projeto, com foco em conhecer e rodar o projeto.

### Atividades Realizadas

| Data       | Atividade                                                   | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                                                                                                                                                                                         | Status    |
| ---------- | ----------------------------------------------------------- | --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| 08/09/2025 | Leitura e estudo da documentação do projeto                 | Estudo                            | [README](https://github.com/EH-FAKE/check-up/blob/develop/README.md)                                                                                                                                    | Concluído |
| 09/09/2025 | Clonagem do fork e preparação do repositório local          | Configuração                      | [Repositório](https://github.com/GCES-EhFake-Fork/checkUp)                                                                                                                                              | Concluído |
| 09/09/2025 | Execução do projeto em ambiente local                       | Código                            | –                                                                                                                                                                                                       | Concluído |
| 09/09/2025 | Execução dos scripts prontos de scraping para testes locais | Código/Teste                      | –                                                                                                                                                                                                       | Concluído |
| 10/09/2025 | Revisão de Pull Request na documentação da equipe           | Doc                               | [PR#13](https://github.com/GCES-EhFake-Fork/docs-interno/pull/13), [PR#17](https://github.com/GCES-EhFake-Fork/docs-interno/pull/17), [PR#20](https://github.com/GCES-EhFake-Fork/docs-interno/pull/20) | Concluído |

### Maiores Avanços

- Consegui rodar a aplicação localmente.
- Entendi melhor a organização do repositório e da documentação.
- Validei o scraping executando rotinas e comandos básicos localmente.

### Maiores Dificuldades

- Ambientação inicial

### Aprendizados

- Fluxo de contribuição do projeto (Issues, PRs e Code Review).
- Passos para executar o projeto localmente.
- Noções iniciais de scraping do projeto.

### Plano Pessoal para a Próxima Sprint

- [ ] Escolher um jornal para início do WebScrapping;
- [ ] Entender melhor o guia de Contribuição
- [ ] Participar com a revisão de 1 PR da equipe;

## Sprint 1 – 15/09 - 24/09

### Resumo da Sprint

Foco em ajustar os scrapers dos portais Globo e Terra para coletar notícias de forma consistente e integrar essas mudanças ao fluxo do projeto, com abertura de PRs no repositório base.

### Atividades Realizadas

| Data       | Atividade                                                          | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                                                   | Status    |
| ---------- | ------------------------------------------------------------------ | --------------------------------- | ----------------------------------------------------------------- | --------- |
| 17/09/2025 | Análise dos scrapers e mapeamento dos portais Globo e Terra        | Estudo                            | –                                                                 | Concluído |
| 23/09/2025 | Ajustes no scraper do portal Globo para capturar notícias          | Código                            | [PR#33](https://github.com/EH-FAKE/check-up/pull/36)              | Concluído |
| 23/09/2025 | Ajustes no scraper do portal Terra para capturar notícias          | Código                            | [PR#36](https://github.com/EH-FAKE/check-up/pull/33)              | Concluído |
| 24/09/2025 | Validação local, testes manuais e revisão dos resultados coletados | Teste/Revisão                     | –                                                                 | Concluído |
| 24/09/2025 | Criação do Relatório da Sprint 1                                   | Doc                               | [PR#39](https://github.com/GCES-EhFake-Fork/docs-interno/pull/39) | Concluído |

### Maiores Avanços

- Scrapers de Globo e Terra atualizados e funcionando para capturar notícias.
- Melhor entendimento do padrão de normalização de notícias do projeto.

### Maiores Dificuldades

- Ajuste de seletores/estruturas devido a variações de layout dos portais.
- Garantir consistência dos campos (título, descrição, conteúdo e tags).

### Aprendizados

- Convenções do projeto para saída de dados e organização dos scrapers.
- Estratégias para tornar seletores mais robustos a mudanças de HTML.

### Plano Pessoal para a Próxima Sprint

- [ ] Acompanhar e endereçar feedbacks até o merge dos PRs (#33 e #36).
- [ ] Avaliar e iniciar contribuição em um próximo portal.

## Sprint 2 – 29/09/2025 - 08/10/2025

### Resumo da Sprint

Foco na inclusão de um novo portal no fluxo do projeto (Agora no Vale), com análise/mapeamento inicial do site, implementação do scraping e validação local por meio de testes manuais. Também foram produzidos e revisados materiais de documentação relacionados à sprint.

### Atividades Realizadas

| Data       | Atividade                                                          | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                                                   | Status    |
| :--------- | :----------------------------------------------------------------- | :-------------------------------- | :---------------------------------------------------------------- | :-------- |
| 01/10/2025 | Análise e mapeamento do portal Agora no Vale                       | Estudo                            |                                                                   | Concluído |
| 05/10/2025 | Implementação do novo portal (Agora no Vale)                       | Código                            | [PR#55](https://github.com/EH-FAKE/check-up/pull/55)              | Concluído |
| 08/10/2025 | Validação local, testes manuais e revisão dos resultados coletados | Teste/Revisão                     |                                                                   | Concluído |
| 08/10/2025 | Revisão de Pull Request na documentação da equipe                  | Doc                               | [PR#56](https://github.com/GCES-EhFake-Fork/docs-interno/pull/56) | Concluído |
| 08/10/2025 | Criação do Relatório da Sprint 2                                   | Doc                               | [PR#62](https://github.com/GCES-EhFake-Fork/docs-interno/pull/62) | Concluído |

### Maiores Avanços

- Novo portal (Agora no Vale) integrado ao fluxo, com scraping implementado e validado localmente.
- Resultados normalizados e revisados para garantir consistência (título, descrição, conteúdo e URL).
- Contribuições de documentação e organização do material da sprint.

### Maiores Dificuldades

- Ajustes finos de seletores devido a variações na estrutura do portal.
- Verificação de qualidade dos resultados coletados durante a validação manual.

### Aprendizados

- Passo a passo para inclusão de um novo portal (análise, implementação e validação).
- Estratégias para tornar os seletores mais robustos frente a mudanças de HTML.

### Plano Pessoal para a Próxima Sprint

- [ ] Acompanhar feedbacks e merge do PR #55.
- [ ] Identificar e iniciar o próximo portal a ser adicionado.

## Sprint 3 – 13/10/2025 - 22/10/2025

### Resumo da Sprint

Foco em revisão de PRs da comunidade Check-up, com execução de testes locais dos scrapers/plays e registro de feedbacks objetivos nos PRs.

### Atividades Realizadas

| Data       | Atividade        | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                                                                   | Status    |
| :--------- | :--------------- | :-------------------------------- | :-------------------------------------------------------------------------------- | :-------- |
| 20/10/2025 | Review do PR #21 | Revisão/Teste                     | [PR#21](https://github.com/EH-FAKE/check-up/pull/21#issuecomment-3432521557)      | Concluído |
| 21/10/2025 | Review do PR #39 | Revisão/Teste                     | [PR#39](https://github.com/EH-FAKE/check-up/pull/39#pullrequestreview-3366075590) | Concluído |
| 22/10/2025 | Review do PR #38 | Revisão/Teste                     | [PR#38](https://github.com/EH-FAKE/check-up/pull/38#pullrequestreview-3366572196) | Concluído |
| 22/10/2025 | Review do PR #53 | Revisão/Teste                     | [PR#53](https://github.com/EH-FAKE/check-up/pull/53#issuecomment-3433160264)      | Concluído |
| 22/10/2025 | Review do PR #65 | Revisão/Teste                     | [PR#65](https://github.com/EH-FAKE/check-up/pull/65#pullrequestreview-3366263188) | Concluído |
| 22/10/2025 | Review do PR #64 | Revisão/Teste                     | [PR#64](https://github.com/EH-FAKE/check-up/pull/64#pullrequestreview-3366480859) | Concluído |

### Maiores Avanços

- Verificação prática dos scrapers e plays em ambiente local
- Melhoria na comunicação com os autores dos PRs, facilitando o alinhamento sobre testes e evidências necessárias.

### Maiores Dificuldades

- Reproduzir cenários específicos por diferenças de ambiente/dados.
- Dependências entre PRs que postergam o merge de algumas mudanças.

### Aprendizados

- Importância de critérios de aceite claros para PRs (escopo, testes, evidências).
- Benefícios de um checklist de revisão para acelerar re-reviews.

### Plano Pessoal para a Próxima Sprint

- [ ] Acompanhar respostas dos autores e realizar re-reviews quando necessário.
- [ ] Revisar novos pull requests.
- [ ] Identificar e iniciar o próximo portal a ser adicionado.

## Sprints 4 – 23/10/2025 - 19/11/2025

### Resumo da Sprint

Apoiar a equipe na revisão de PRs e implementar novos portais (Cidade Verde e Faxaju), além de resolver conflitos de PRs antigos para manter as contribuições atualizadas com o projeto.

### Atividades Realizadas

| Data       | Atividade                                                                                                                   | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                                                                                            | Status    |
| ---------- | --------------------------------------------------------------------------------------------------------------------------- | --------------------------------- | ---------------------------------------------------------------------------------------------------------- | --------- |
| 05/11/2025 | Acompanhamento das respostas e apoio à equipe na identificação e esclarecimento de problemas em PRs revisados               | Discussão/Revisão                 | –                                                                                                          | Concluído |
| 10/11/2025 | Início dos estudos e mapeamento dos portais Cidade Verde e Faxaju para futura implementação                                 | Estudo                            | –                                                                                                          | Concluído |
| 19/11/2025 | Implementação dos scrapers/spiders dos portais Cidade Verde e Faxaju                                                        | Código/Teste                      | [PR#80](https://github.com/EH-FAKE/check-up/pull/80), [PR#82](https://github.com/EH-FAKE/check-up/pull/82) | Concluído |
| 19/11/2025 | Resolução de conflitos em PRs antigos ainda não aceitos, atualizando branches e ajustando código conforme mudanças recentes | Código/Revisão                    | –                                                                                                          | Concluído |

### Maiores Avanços

- Conclusão da implementação dos portais Cidade Verde e Faxaju, ampliando a cobertura de coleta de notícias do projeto.
- Maior participação no acompanhamento de PRs, ajudando a equipe a entender e resolver problemas apontados nas revisões.
- Resolução de conflitos de PRs antigos, destravando a possibilidade de merge e mantendo as contribuições atualizadas.

### Maiores Dificuldades

- Tempo de análise inicial dos novos portais até encontrar padrões viáveis para coleta.
- Lidar com conflitos em PRs mais antigos devido ao volume de mudanças acumuladas no branch principal.
- Garantir que os novos portais se mantivessem alinhados com os padrões e estrutura dos scrapers já existentes.

### Aprendizados

- Melhores práticas para comunicar problemas encontrados em PRs e apoiar autores na correção.
- Estratégias iniciais para estudar novos portais (mapeamento de estrutura de HTML, URLs e padrões de conteúdo).
- Melhores práticas para resolução de conflitos (rebase/merge, análise cuidadosa das mudanças e testes após ajustes).
- Cuidados ao adicionar novos portais para manter consistência com os scrapers já implementados.

### Plano Pessoal para a Próxima Sprint

- [ ] Acompanhar feedbacks e merge dos PRs #80 e #82.
- [ ] Monitorar os novos portais implantados e ajustar se surgirem problemas.
- [ ] Continuar ajudando na resolução de conflitos ou ajustes em PRs pendentes.
