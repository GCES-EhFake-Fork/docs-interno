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


### Maiores Dificuldades

*   A documentação não detalha explicitamente a organização da equipe em termos de papéis específicos ou a existência de uma gitpage dedicada, exigindo inferência a partir das práticas de contribuição e da estrutura dos repositórios.
*   A ausência de menção a canais de comunicação externos (chat, fóruns) exigiu a suposição de que a comunicação é centralizada no GitHub e através da documentação.
*   Dificuldade inicial em entender onde trabalhar as contribuições, confundi com o RAG no GitLab, mas depois esclarecido que o foco é no GitHub.

### Aprendizados

*   A importância de uma documentação clara e abrangente para projetos de código aberto, especialmente para a configuração do ambiente e o fluxo de contribuição, e como ela complementa o próprio código.
*   O valor de ferramentas como Docker, `Makefile` e MkDocs para simplificar o setup e automatizar tarefas complexas em projetos de software e documentação.
*   A relevância de padrões de código (Git Flow, Conventional Commits) e processos de revisão (PRs obrigatórios), juntamente com um Código de Conduta, para garantir a qualidade, a colaboração e um ambiente saudável em equipes de desenvolvimento.


### Plano Pessoal para a Próxima Sprint

* [ ] Aprofundar na estrutura dos spiders e plays, talvez implementando um spider/play simples para um novo portal de notícias no repositório `check-up`.
* [ ] Se necessário, contribuir com melhorias na documentação, especialmente em áreas que possam beneficiar novos colaboradores.


## Sprint 1 – 15/09/2025 - 24/09/2025

### Resumo da Sprint
Esta sprint foi dedicada ao **início da implementação de um novo web scraping para o Jornal de Brasília**. O objetivo principal foi estabelecer a estrutura inicial para a extração de notícias deste portal, seguindo os padrões do projeto Check-up. As atividades incluíram a criação de uma nova branch (`feat/jornalDeBrasília`) para isolar o desenvolvimento e a configuração dos componentes essenciais para a coleta de dados. O foco foi em garantir que a base para o novo spider estivesse funcional e pronta para a próxima fase de desenvolvimento.

### Atividades Realizadas
| Data | Atividade | Tipo (Código/Doc/Discussão/Outro) | Link/Referência | Status |
|------------|-----------------------------------------------|-----------------------------------|-----------------------------------------------------|-----------|
| 17/09/2025 | Início da análise do site Jornal de Brasília | Estudo/Doc | [Jornal de Brasília](https://www.jornaldebrasilia.com.br/) | Concluído |
| 20/09/2025 | Dificuldade/Tentativa de rodar os make scrape | Código | - | Concluído |
| 24/09/2025 | Desenvolvimento da estrutura básica do spider | Código | [Commit](https://github.com/GCES-EhFake-Fork/checkUp/commit/44e17b06877b41d161e2117051cad2a4a1c30339) | Concluído |
| 24/09/2025 | Desenvolvimento da estrutura do Scrapping(Plays) | Código | - | Em Andamento |

### Maiores Avanços
*   **Criação da branch dedicada**: A branch `feat/jornalDeBrasília` foi criada, garantindo um ambiente de desenvolvimento isolado para a nova funcionalidade.
*   **Análise inicial do portal**: Foi realizada uma análise preliminar da estrutura do site do Jornal de Brasília para identificar padrões de notícias e elementos a serem extraídos.
*   **Estrutura básica do spider**: A base para o novo spider foi desenvolvida

### Maiores Dificuldades
*   **Variações na estrutura do site**: O site do Jornal de Brasília apresenta algumas variações na estrutura HTML entre diferentes tipos de notícias, o que exigiu um planejamento mais detalhado para a extração robusta de dados.
*   **Erros ao rodar o scrape existente**: Dificuldade inicial em fazer o projeto rodar devido a erros no scrape já implementado, o que atrasou o início do desenvolvimento do novo spider.

### Aprendizados
*   A importância de uma análise aprofundada da estrutura do site antes de iniciar a codificação do spider para prever e mitigar dificuldades.
*   Entendimento por completo de como funciona a pipeline de dados do Check-up, desde a coleta até o processamento das notícias.

### Plano Pessoal para a Próxima Sprint
*   **[ ] Concluir a implementação do spider e play para o Jornal de Brasília**: Finalizar o desenvolvimento do spider, garantindo a coleta de URLs do Jornal, bem como o desenvolvimento do play para processar essas URLs.
*   **[ ] Adicionar tratamento de erros e robustez**: Tratar possíveis variações, por exemplo, está retornando URLs gerais que não são notícias.


## Sprint 2 – 25/09/2025 - 08/10/2025

### Resumo da Sprint
Esta sprint foi dedicada à **conclusão do web scraping para o Jornal de Brasília** e ao aprofundamento dos conhecimentos sobre a pipeline geral, permitiu a concretização do conhecimento em realação as etapas principais, sendo elas: crawling, scraping e armazenamento.. O objetivo principal foi finalizar a implementação da extração de notícias deste portal, garantindo sua funcionalidade e robustez. As atividades incluíram a depuração, otimização e validação do spider e play.

### Atividades Realizadas
| Data | Atividade | Tipo (Código/Doc/Discussão/Outro) | Link/Referência | Status |
|------------|-----------------------------------------------|-----------------------------------|-----------------------------------------------------|-----------|
| 25/09/2025 | Continuação do desenvolvimento da play | Código | - | Concluído |
| 30/09/2025 | Debug e otimização da play do Jornal de Brasília | Código | - | Concluído |
| 01/10/2025 | Estudo e aprofundamento da Play, seleção e escolha correta dos seletores | Estudo/Doc | - | Concluído |
| 07/10/2025 | Conclusão do scrapping do Jornal de Brasília e Abri uma issue relacionada | Código | [PR#53](https://github.com/EH-FAKE/check-up/pull/53)  [Issue#50](https://github.com/EH-FAKE/check-up/issues/50) | Concluído |

### Maiores Avanços
*   **Conclusão da play do Jornal de Brasília**: O play para o Jornal de Brasília foi finalizado, testado e validado, garantindo a extração completa dos dados das notícias (título, URL, corpo e descrição) usando as URLs coletadas. 
*   **Aprofundamento técnico**: Maior entendimento sobre o funcionamento e a integração das ferramentas Aplay e Spider no fluxo de trabalho.

### Maiores Dificuldades
*   Dificuldade na seleção dos seletores.

### Aprendizados
*   Aprofundamento no funcionamento e integração das etapas do scrapping, compreendendo melhor seus conceitos e aplicações.
*   Reforço da importância da análise prévia da estrutura do site para o desenvolvimento eficiente de spiders.

### Plano Pessoal para a Próxima Sprint
*   **[ ] Iniciar o desenvolvimento de um novo portal**: Começar a análise e implementação do web scraping para um novo portal, aplicando os conhecimentos adquiridos.
