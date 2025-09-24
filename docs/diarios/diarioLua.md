# Diário de Bordo – Luana Medeiros

**Disciplina:** Gerência de Configuração e Evolução de Software

**Equipe:** WebScrapping

**Comunidade/Projeto de Software Livre:** Check-up

---

## Sprint 0 – 02/09/2025 - 10/09/2025

### Resumo da Sprint

Nesta sprint, o foco esteve no reconhecimento inicial do projeto, por meio da leitura da documentação e análise dos repositórios no GitHub. Foram realizadas atividades de configuração do ambiente, estudo das políticas de governança, comunicação e engenharia de software, além da contribuição para a documentação da equipe. O objetivo principal foi estabelecer uma base de conhecimento sólida sobre os projetos e seu funcionamento, de forma a preparar terreno para contribuições mais efetivas nas próximas etapas da disciplina.

### Atividades Realizadas

| Data          | Atividade                                    | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                                                                                                      | Status    |
| ------------- | -------------------------------------------- | --------------------------------- | -------------------------------------------------------------------------------------------------------------------- | --------- |
| 06/09         | Leitura da Documentação do projeto Base      | Estudo/Ambientação                | [Docs](https://eh-fake.github.io/docs/land/index.html)                                                               | Concluído |
| 06/09         | Leitura do `README.md` do Projeto Base       | Estudo/Ambientação                | [README](https://github.com/EH-FAKE/check-up/blob/develop/README.md)                                                 | Concluído |
| 08/09         | Clonagem do Fork do Repositório              | Configuração                      | [Repositório](https://github.com/GCES-EhFake-Fork/checkUp)                                                           | Concluído |
| 08/09 - 09/09 | Configuração do Ambiente Local               | Configuração                      | [Repositório](https://github.com/GCES-EhFake-Fork/checkUp)                                                           | Concluído |
| 09/09         | Execução de comandos de scrapping para teste | Configuração                      | [Repositório](https://github.com/GCES-EhFake-Fork/checkUp)                                                           | Concluído |
| 10/09         | Criação do Diário de Bordo                   | Doc                               | [Documento](https://github.com/GCES-EhFake-Fork/docs-interno/blob/main/docs/grupo-webscrapping/sprint0/diarioLua.md) | Concluído |

### Maiores Avanços

- Aprendi a rodar a aplicação e configurar o ambiente.
- Entendi a arquitetura dos projetos Check-up e EhFake.
- Conheci as regras de contribuição.
- Compreendi as formas de contribuição na disciplina.

### Maiores Dificuldades

- Entender a arquitetura e os objetivos do projeto.
- Dificuldade em se situar e compreender a forma de contribuição.
- Pouco tempo para absorver a complexidade e as regras do projeto.

### Aprendizados

- Uso básico de GitHub Issues.
- Fluxo de contribuição do projeto.

### Plano Pessoal para a Próxima Sprint

- [ ] Contribuir com pelo menos 1 PR.
- [ ] Participar da revisão de código de um colega.

## Sprint 1 – 15/09 a 24/09

### Resumo da Sprint

O principal objetivo desta sprint foi desenvolver os scrapers dos portais **Brasil de Fato** e **Agência Pública**, garantindo a coleta consistente de notícias e integrando as implementações ao fluxo do projeto, por meio da abertura de PRs no repositório principal.

### Atividades Realizadas

| Data       | Atividade                                                                             | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                                                                                               | Status    |
| ---------- | ------------------------------------------------------------------------------------- | --------------------------------- | ------------------------------------------------------------------------------------------------------------- | --------- |
| 18/09/2025 | Estudo e mapeamento dos portais para implementação dos scrapers                       | Estudo                            | –                                                                                                             | Concluído |
| 24/09/2025 | Início da codificação local dos scrapers dos portais Brasil de Fato e Agência Pública | Código                            | –                                                                                                             | Concluído |
| 24/09/2025 | Abertura dos PRs em rascunho com a implementação inicial dos scrapers                 | Código                            | [PR#39](https://github.com/EH-FAKE/check-up/pull/39)<br> [PR#40](https://github.com/EH-FAKE/check-up/pull/40) | Concluído |
| 24/09/2025 | Elaboração e submissão do relatório da Sprint 1                                       | Doc                               | [PR#41](https://github.com/GCES-EhFake-Fork/docs-interno/pull/41)                                             | Concluído |

### Maiores Avanços

- Melhor compreensão do padrão de normalização de notícias no projeto.
- Scrapers para os portais Brasil de Fato e Agência Pública concluídos em versão inicial (draft).
- PRs abertos para revisão da equipe e mantenedores.

### Maiores Dificuldades

- Garantir consistência nos campos de saída (título, descrição, conteúdo e tags).
- Organização da carga horária entre desenvolvimento e testes.

### Aprendizados

- Padrões do projeto para padronização dos dados e estruturação dos scrapers.
- Técnicas para criar seletores mais resilientes a mudanças no HTML dos portais.

### Plano Pessoal para a Próxima Sprint

- [ ] Acompanhar e aplicar os feedbacks dos PRs (#39 e #40) até o merge.
- [ ] Avaliar e iniciar a contribuição em um novo portal.
