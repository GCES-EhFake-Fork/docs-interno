# Diário de Bordo – Gabriel Monteiro

**Disciplina:** Gerência e Configuração de Software
**Equipe:** WebScrapping
**Comunidade/Projeto de Software Livre:** É Fake

---

## Sprint 0 – 02/09 - 10/09

### Resumo da Sprint

Nesta sprint o enfoque foi compreender melhor sobre o projeto e sobre a ideia de contribuição para a disciplina, entendendo melhor sobre o projeto e o EhFake, tanto a documentação quanto o projeto. À luz dessa perspectiva, como demorei para entrar na disciplina, a atividade foi estudar sobre os repositórios do GitHub, olhando a parte de documentação e do projeto, estabelecendo um conhecimento para que possa ser possível contribuir durante a disciplina.

### Atividades Realizadas

| Data       | Atividade                                               | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                                                                                            | Status    |
| ---------- | ------------------------------------------------------- | --------------------------------- | ---------------------------------------------------------------------------------------------------------- | --------- |
| 08/09/2025 | Leitura e compreensão do projeto                        | Doc                               | [EhFake](https://github.com/EH-FAKE/check-up)                                                              | Concluído |
| 08/09/2025 | Estudo e compreensão do projeto Check Up                | Estudo/Doc                        | [Check Up](https://github.com/EH-FAKE/check-up/blob/develop/README.md)                                     | Concluído |
| 09/09/2025 | Configuração e ambientação do projeto no ambiente local | Código                            | -                                                                                                          | Concluído |
| 09/09/2025 | Maior estudo e aprendizado do Check Up                  | Estudo/Doc                        | [Check Up](https://github.com/EH-FAKE/check-up/blob/develop/README.md)                                     | Concluído |
| 10/09/2025 | Contribuição com a documentação da Equipe               | Código                            | [Commit](https://github.com/GCES-EhFake-Fork/docs-interno/commit/fb46aa7414b99f0c8a4d898c421a7d6fa4c62cd0) | Concluído |

### Maiores Avanços

- Compreensão do Código de conduta e do Contributing
- Compreensão do Check Up e do EhFake
- Compreensão das formas de contribuição para a disciplina

### Maiores Dificuldades

- Dificuldade em me situar no projeto pelo atraso
- Dificuldade em entender a forma de contribuição para o projeto
- Pouco tempo para absorver toda a função do projeto e sua arquitetura

### Aprendizados

- A importância e como usar bem o Docker e um deploy automático
- Como a IA pode auxiliar na verificação de informações que somos bombardeados diariamente
- Fluxo de contribuição do projeto.

### Plano Pessoal para a Próxima Sprint

- [x] Contribuir com o projeto e a equipe para o desenvolvimento do projeto
- [x] Compreender melhor sobre a arquitetura e onde podemos contribuir no projeto

## Sprint 1 – 11/09 - 24/09

### Resumo da Sprint

Nesta sprint o foco foi avançar da etapa de estudo inicial para a **primeira contribuição efetiva** ao repositório. Após entender a base do projeto e como funciona a arquitetura do EhFake, passei a atuar diretamente no repositório `checkUp`, criando uma issue no projeto original para propor melhoria de documentação sobre uso de `pre-commit`, alinhado ao fluxo de contribuição da disciplina. Esse passo foi importante porque marcou o início das contribuições práticas e da interação com a comunidade do projeto.

### Atividades Realizadas

| Data       | Atividade                                                                 | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                                                                                                 | Status       |
| ---------- | ------------------------------------------------------------------------- | --------------------------------- | --------------------------------------------------------------------------------------------------------------- | ------------ |
| 17/09/2025 | Estudo sobre CI existente (`Check-up CI`) no repositório                  | Estudo/Doc                        | [ci.yml](https://github.com/EH-FAKE/check-up/blob/develop/.github/workflows/ci.yml)                             | Concluído    |
| 18/09/2025 | Preparação de arquivo `.pre-commit-config.yaml`                           | Código                            | -                                                                                                               | Concluído    |
| 19/09/2025 | Redação de instruções no `README.md` para orientar novos contribuidores   | Doc                               | -                                                                                                               | Concluído    |
| 20/09/2025 | Discussão sobre fluxo de PR em forks e como referenciar issues originais  | Discussão                         | -                                                                                                               | Concluído    |
| 23/09/2025 | Abertura da **Issue #30** propondo documentação sobre uso de `pre-commit` | Doc                               | [Issue #30](https://github.com/EH-FAKE/check-up/issues/30)                                                      | Concluído    |
| 23/09/2025 | Preparação do branch e commit vinculando à issue aberta                   | Código                            | [Commit vinculado à Issue #30](https://github.com/GCES-EhFake-Fork/checkUp/commit/...) _(substituir pelo link)_ | Pendente PR  |
| 24/09/2025 | Planejamento para abrir o PR no repositório original                      | Discussão/Planejamento            | -                                                                                                               | Em andamento |

### Maiores Avanços

- Consegui abrir minha primeira issue no projeto original (`#30`).
- Avancei do estudo para a prática, criando arquivo de configuração e instruções no `README.md`.
- Aprendi como referenciar issues no commit/PR de um fork para o repositório original.

### Maiores Dificuldades

- Entender como não duplicar esforços já feitos no CI existente.
- Dificuldade em commitar para o repositório original.
- Adaptação ao fluxo de contribuição open-source (fork → branch → PR → issue).

### Aprendizados

- Importância do `pre-commit` para reforçar a governança de código antes do push.
- Como workflows de CI existentes podem ser complementados por ferramentas locais.

### Plano Pessoal para a Próxima Sprint

- [ ] Finalizar e abrir o PR referente à issue #30 no repositório original.
- [ ] Acompanhar o feedback da comunidade/mantenedores sobre a contribuição.
- [ ] Buscar uma nova oportunidade de contribuição, de preferência no código (scrapers ou testes).
- [ ] Aprofundar entendimento das migrations e arquitetura do banco de dados do projeto.
