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
| 10/09/2025 | Revisão de Pull Request na documentação da equipe           | Revisão/Doc                       | [PR#13](https://github.com/GCES-EhFake-Fork/docs-interno/pull/13), [PR#17](https://github.com/GCES-EhFake-Fork/docs-interno/pull/17), [PR#20](https://github.com/GCES-EhFake-Fork/docs-interno/pull/20) | Concluído |

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

| Data       | Atividade                                                          | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                                      | Status    |
| ---------- | ------------------------------------------------------------------ | --------------------------------- | ---------------------------------------------------- | --------- |
| 17/09/2025 | Análise dos scrapers e mapeamento dos portais Globo e Terra        | Estudo                            | –                                                    | Concluído |
| 23/09/2025 | Ajustes no scraper do portal Globo para capturar notícias          | Código                            | [PR#33](https://github.com/EH-FAKE/check-up/pull/33) | Concluído |
| 23/09/2025 | Ajustes no scraper do portal Terra para capturar notícias          | Código                            | [PR#36](https://github.com/EH-FAKE/check-up/pull/36) | Concluído |
| 24/09/2025 | Validação local, testes manuais e revisão dos resultados coletados | Teste/Revisão                     | –                                                    | Concluído |

### Maiores Avanços

- Scrapers de Globo e Terra atualizados e funcionando para capturar notícias.
- Melhor entendimento do padrão de normalização de notícias do projeto.

### Maiores Dificuldades

- Ajuste de seletores/estruturas devido a variações de layout dos portais.
- Garantir consistência dos campos (título, data, autor e conteúdo).

### Aprendizados

- Convenções do projeto para saída de dados e organização dos scrapers.
- Estratégias para tornar seletores mais robustos a mudanças de HTML.

### Plano Pessoal para a Próxima Sprint

- [ ] Acompanhar e endereçar feedbacks até o merge dos PRs (#33 e #36).
- [ ] Avaliar e iniciar contribuição em um próximo portal.
