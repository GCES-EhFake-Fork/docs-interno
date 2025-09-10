# Diário de Bordo – Eduardo de Almeida Ferreira

**Disciplina:** Gerência de Configuração e Evolução de Software

**Equipe:** WebScrapping

**Comunidade/Projeto de Software Livre:** Check-up


## Sprint 0 – 02/09/2025 - 10/09/2025

### Resumo da Sprint

Esta sprint focou na compreensão inicial dos projetos Check-up (extração de conteúdo de notícias) e EhFake (documentação do projeto). As atividades incluíram a análise da estrutura de ambos os repositórios GitHub, o mapeamento das políticas de Governança, Comunicação e Engenharia de Software e a documentação dos aprendizados sobre a configuração do ambiente de desenvolvimento. O objetivo foi estabelecer uma base de conhecimento abrangente para futuras contribuições, considerando a interconexão entre o código e a documentação.

### Atividades Realizadas

| Data       | Atividade                                     | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                                     | Status    |
|------------|-----------------------------------------------|-----------------------------------|-----------------------------------------------------|-----------|
| 03/09/2025 | Primeiro contato com o projeto  | Código/Doc                        | [Repositório](https://github.com/EH-FAKE/check-up)                 | Concluído |
| 06/09/2025 | Leitura e análise do `README.md` (`check-up`) | Estudo/Doc                        | [Repositório](https://github.com/EH-FAKE/check-up/blob/develop/README.md)                     | Concluído |
| 06/09/2025 | Execução do projeto em ambiente local | Código                       | -                   | Concluído |
| 08/09/2025 | Leitura e análise do `TUTORIAL_CRIACAO_DO_ZERO.md` (`check-up`) | Estudo/Doc                        | [Repositório](https://github.com/EH-FAKE/check-up/blob/develop/TUTORIAL_CRIACAO_DO_ZERO.md)        | Concluído |
| 08/09/2025 | Leitura e análise do `TUTORIAL_SPIDERS_PLAYS.md` (`check-up`) | Estudo/Doc                        | [Repositório](https://github.com/EH-FAKE/check-up/blob/develop/TUTORIAL_SPIDERS_PLAYS.md)         | Concluído |
| 09/09/2025 | Contribuição com a documentação da Equipe   | Código                       |    [Commit](https://github.com/GCES-EhFake-Fork/docs-interno/commit/fb46aa7414b99f0c8a4d898c421a7d6fa4c62cd0)                       | Concluído |



### Maiores Avanços

*   Compreensão aprofundada da arquitetura do projeto Check-up (Spiders e Plays) e sua relação com a documentação do EhFake.
*   Entendimento do fluxo de contribuição unificado, incluindo o uso de Git Flow, Conventional Commits e o Código de Conduta.
*   Identificação dos pré-requisitos e do processo de setup do ambiente via Docker e `make setup` para o projeto de código, e MkDocs para a documentação.


## Maiores Dificuldades

*   A documentação não detalha explicitamente a organização da equipe em termos de papéis específicos ou a existência de uma gitpage dedicada, exigindo inferência a partir das práticas de contribuição e da estrutura dos repositórios.
*   A ausência de menção a canais de comunicação externos (chat, fóruns) exigiu a suposição de que a comunicação é centralizada no GitHub e através da documentação.
*   Dificuldade inicial em entender onde trabalhar as contribuições, confundi com o RAG no GitLab, mas depois esclarecido que o foco é no GitHub.

## Aprendizados

*   A importância de uma documentação clara e abrangente para projetos de código aberto, especialmente para a configuração do ambiente e o fluxo de contribuição, e como ela complementa o próprio código.
*   O valor de ferramentas como Docker, `Makefile` e MkDocs para simplificar o setup e automatizar tarefas complexas em projetos de software e documentação.
*   A relevância de padrões de código (Git Flow, Conventional Commits) e processos de revisão (PRs obrigatórios), juntamente com um Código de Conduta, para garantir a qualidade, a colaboração e um ambiente saudável em equipes de desenvolvimento.


## Plano Pessoal para a Próxima Sprint

* [ ] Aprofundar na estrutura dos spiders e plays, talvez implementando um spider/play simples para um novo portal de notícias no repositório `check-up`.
* [ ] Se necessário, contribuir com melhorias na documentação, especialmente em áreas que possam beneficiar novos colaboradores.
