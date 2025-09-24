# 📝 Relatório de Contribuição – Sprint 1

**Disciplina:** Gestão de Configuração e Evolução de Software
**Equipe:** EH-FAKE
**Comunidade/Projeto de Software Livre:** EH-FAKE
**Período da Sprint:** 15/09/2025 à 24/09/2025

---

## 1. Objetivos da Sprint

- [ ] Efetuar as primeiras contribuições no repositório base
- [ ] Atualizar scrapers já existentes no projeto para capturar notícias
- [ ] Desenvolver novos scrapers para ampliar a cobertura
- [ ] Melhorar a organização do repositório (templates de issue e automações de CI)
- [ ] Garantir a atualização contínua da documentação interna do time

---

## 2. Entregas Coletivas

| Entrega                                        | Status (Concluído/Parcial/Pendente) | Link/Referência                                                                                                                                                  | Observações      |
| ---------------------------------------------- | ----------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- |
| Atualização dos scrapers (Globo, Terra, RBS)   | Parcial                             | [PR#33](https://github.com/EH-FAKE/check-up/pull/33), [PR#36](https://github.com/EH-FAKE/check-up/pull/36), [PR#38](https://github.com/EH-FAKE/check-up/pull/38) | RBS em andamento |
| Criação de novos scrapers                      | Pendente                            | [PR#40](https://github.com/EH-FAKE/check-up/pull/40), [PR#39](https://github.com/EH-FAKE/check-up/pull/39)                                                       |                  |
| Novos templates de Issue e ajustes de contato  | Concluído                           | [PR#29](https://github.com/EH-FAKE/check-up/pull/29), [PR#24](https://github.com/EH-FAKE/check-up/pull/24)                                                       |                  |
| Automação (CI) para Issues                     | Concluído                           | [PR#28](https://github.com/EH-FAKE/check-up/pull/28)                                                                                                             |                  |
| Atualizações na documentação interna da equipe | Concluído                           | [docs](https://gces-ehfake-fork.github.io/docs-interno/)                                                                                                         |                  |

---

## 3. Contribuições Individuais

| Integrante       | Contribuições                                                                                                                                              | Links (PRs, Issues, Docs)                                                                                                                                                                                                                                                                          | Observações |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- |
| Alana            | Ajustes nos scrapers Globo e Terra; validação local e testes; Relatório da Sprint 1                                                                        | [PR#33](https://github.com/EH-FAKE/check-up/pull/33), [PR#36](https://github.com/EH-FAKE/check-up/pull/36), [PR#39](https://github.com/GCES-EhFake-Fork/docs-interno/pull/39)                                                                                                                      |             |
| Ana              |                                                                                                                                                            |                                                                                                                                                                                                                                                                                                    |             |
| Carlos           |                                                                                                                                                            |                                                                                                                                                                                                                                                                                                    |             |
| Daniel           | Fork do repositório oficial da documentação do Eh Fake, contribuição com novos Template Issues, Orientações de Contato e Pipelines de automação de issues. | [Fork](https://github.com/GCES-EhFake-Fork/docsOficialEhFake), [PR#29](https://github.com/EH-FAKE/check-up/pull/29), [PR#24](https://github.com/EH-FAKE/check-up/pull/24), [PR#28](https://github.com/EH-FAKE/check-up/pull/28), [PR#32](https://github.com/GCES-EhFake-Fork/docs-interno/pull/32) |             |
| Eduardo          |                                                                                                                                                            |                                                                                                                                                                                                                                                                                                    |             |
| Felipe de Sousa  |                                                                                                                                                            |                                                                                                                                                                                                                                                                                                    |             |
| Gabriel Monteiro |                                                                                                                                                            |                                                                                                                                                                                                                                                                                                    |             |
| Lua Medeiros     |                                                                                                                                                            |                                                                                                                                                                                                                                                                                                    |             |
| Luciano          |    Criação guia de contribuição e código de conduta para comunidade EhFake                                                                                                                                                        |                                                                                                                                                                                                                                                                                                    |        [PR#21](https://github.com/EH-FAKE/check-up/pull/21)     |
| Pedro Ferreira   |                                                                                                                                                            |                                                                                                                                                                                                                                                                                                    |             |
| Pedro Silva      |                                                                                                                                                            |                                                                                                                                                                                                                                                                                                    |             |
| Yago             |                                                                                                                                                            |                                                                                                                                                                                                                                                                                                    |             |
| Vinicius         |                                                                                                                                                            |                                                                                                                                                                                                                                                                                                    |             |

---

## 4. Maiores Avanços

✨ Destaques da Sprint:

- Primeiras contribuições efetivas no repositório base.
- Criação da Guia de Contribuição e Código de Conduta.
- Adaptação de scrapers existentes (Globo, Terra, RBS, etc) para extrair conteúdo de notícias em vez de anúncios.
- Criação de novos scrapers: Agência Pública, Brasil de Fato, Jornal de Brasília.
- Organização e automação do repositório: novos templates de issue, correções e automações via GitHub Actions

---

## 5. Maiores Dificuldades

Principais desafios enfrentados:

- Ajuste de seletores e variações de layout dos portais impactando scrapers.
- Configuração/execução do ambiente local (incluindo Docker) para alguns membros.
- Garantir consistência dos campos coletados (título, descrição, conteúdo e tags).

---

## 6. Lições Aprendidas

- Boas práticas de GCES (templates, automações) facilitam a colaboração.
- Estratégias de scraping mais robustas contra mudanças de HTML são essenciais.
- Importância do pre-commit e de padronizações para qualidade dos PRs.
- Fluxo de contribuição (issue → branch → PR → revisão) mais fluido após a prática.

---

## 7. Planejamento para a Próxima Sprint

- [ ] Acompanhar feedbacks e realizar ajustes até o merge dos PRs abertos.
- [ ] Selecionar e iniciar um novo portal para contribuição em scraping.
- [ ] Avançar em testes/validações de scrapers existentes e dados coletados.
- [ ] Manter os diários de bordo atualizados com links definitivos de PRs/issues.
