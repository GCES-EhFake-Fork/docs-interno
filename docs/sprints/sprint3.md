# 📝 Relatório de Contribuição – Sprint 3

**Disciplina:** Gestão de Configuração e Evolução de Software
**Equipe:** EH-FAKE
**Comunidade/Projeto de Software Livre:** EH-FAKE / Check-up
**Período da Sprint:** 09/10/2025 à 22/10/2025

---

## 1. Objetivos da Sprint

- [ ] Centralizar a documentação no repositório principal (branch dedicada)
- [ ] Evoluir a cobertura de portais (novos scrapers e correções)
- [ ] Entregar melhorias de usabilidade no Front-end
- [ ] Revisar e testar PRs, fornecendo feedback acionável
- [ ] Manter a documentação interna atualizada

---

## 2. Entregas Coletivas

| Entrega                                                                   | Status (Concluído/Parcial/Pendente) | Link/Referência                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Observações                           |
| :------------------------------------------------------------------------ | :---------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------ |
| Centralização da documentação em branch dedicada no repositório principal | Concluído                           | [PR#62](https://github.com/EH-FAKE/check-up/pull/62), [Issue#63](https://github.com/EH-FAKE/check-up/issues/63)                                                                                                                                                                                                                                                                                                                                                                                        | Migração do repo `EH-FAKE/docs`       |
| Novos scrapers/correções: Poder360 e Jornal da Paraíba                    | Concluído                           | [PR#64](https://github.com/EH-FAKE/check-up/pull/64), [PR#65](https://github.com/EH-FAKE/check-up/pull/65)                                                                                                                                                                                                                                                                                                                                                                                             | Correção de extração no Poder360      |
| Melhorias no Front-end (UI + Favoritos)                                   | Concluído                           | [PR#58](https://github.com/EH-FAKE/check-up/pull/58), [PR#60](https://github.com/EH-FAKE/check-up/pull/60)                                                                                                                                                                                                                                                                                                                                                                                             | Usabilidade e organização de notícias |
| Revisões técnicas e testes de PRs                                         | Concluído                           | [PR#21](https://github.com/EH-FAKE/check-up/pull/21#issuecomment-3432521557), [PR#38](https://github.com/EH-FAKE/check-up/pull/38#pullrequestreview-3366572196), [PR#39](https://github.com/EH-FAKE/check-up/pull/39#pullrequestreview-3366075590), [PR#53](https://github.com/EH-FAKE/check-up/pull/53#issuecomment-3433160264), [PR#64](https://github.com/EH-FAKE/check-up/pull/64#pullrequestreview-3366480859), [PR#65](https://github.com/EH-FAKE/check-up/pull/65#pullrequestreview-3366263188) | Feedback acionável e validação local  |

---

## 3. Contribuições Individuais

| Integrante     | Contribuições principais                                                                                             | Links (PRs, Issues, Docs)                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| -------------- | -------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Alana          | Revisão em PRs e Criação do relatório da Sprint 3                                                                    | [PR#21](https://github.com/EH-FAKE/check-up/pull/21#issuecomment-3432521557), [PR#38](https://github.com/EH-FAKE/check-up/pull/38#pullrequestreview-3366572196), [PR#39](https://github.com/EH-FAKE/check-up/pull/39#pullrequestreview-3366075590), [PR#53](https://github.com/EH-FAKE/check-up/pull/53#issuecomment-3433160264), [PR#64](https://github.com/EH-FAKE/check-up/pull/64#pullrequestreview-3366480859), [PR#65](https://github.com/EH-FAKE/check-up/pull/65#pullrequestreview-3366263188) |
| Ana            | —                                                                                                                    | —                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Carlos         | Desenvolvimento de testes de integração dos scrapers e criação de comando Make para execução dos testes.             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Daniel         | Centralização da documentação: análise, migração de conteúdo e abertura de PR/Issue dedicados.                       | [PR#62](https://github.com/EH-FAKE/check-up/pull/62), [Issue#63](https://github.com/EH-FAKE/check-up/issues/63)                                                                                                                                                                                                                                                                                                                                                                                        |
| Eduardo        | Centralização da documentação em dupla; ajustes no play do Jornal de Brasília conforme review (remoção do Chromium). | [PR#62](https://github.com/EH-FAKE/check-up/pull/62), [Issue#63](https://github.com/EH-FAKE/check-up/issues/63), [Commit](https://github.com/EH-FAKE/check-up/pull/53/commits/cd814a6ae7dc245f838d00c6c3b1e909cac5c1cd), [Commit](https://github.com/GCES-EhFake-Fork/checkUp/commit/9766c9b2f0d8180bdb848706bf8eea26c7ff6fa4)                                                                                                                                                                         |
| Felipe         | Documentação do framework de testes; criação de issue de melhorias; revisão relacionada ao PR#39.                    | [PR#23 (fork)](https://github.com/GCES-EhFake-Fork/checkUp/pull/23), [Issue#22 (fork)](https://github.com/GCES-EhFake-Fork/checkUp/issues/22), [PR#39](https://github.com/EH-FAKE/check-up/pull/39)                                                                                                                                                                                                                                                                                                    |
| Gabriel        | —                                                                                                                    | —                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Lua            | —                                                                                                                    | —                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Luciano        | —                                                                                                                    | —                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Mateus Levy    | Correções no Poder360 e criação do spider/scraper do Jornal da Paraíba; submissão de PRs.                            | [PR#64](https://github.com/EH-FAKE/check-up/pull/64), [PR#65](https://github.com/EH-FAKE/check-up/pull/65), [Commit](https://github.com/GCES-EhFake-Fork/checkUp/commit/7930a91)                                                                                                                                                                                                                                                                                                                       |
| Pedro Ferreira | —                                                                                                                    | —                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Pedro Silva    | —                                                                                                                    | —                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Vinicius       | Melhorias no Front-end: ajustes de UI e área de notícias favoritas.                                                  | [PR#58](https://github.com/EH-FAKE/check-up/pull/58), [PR#60](https://github.com/EH-FAKE/check-up/pull/60)                                                                                                                                                                                                                                                                                                                                                                                             |
| Yago           | Finalização do spider e play do Congresso em Foco; testes e ajustes; abertura de PRs.                                | [PR#30 (fork)](https://github.com/GCES-EhFake-Fork/checkUp/pull/30), [PR#66](https://github.com/EH-FAKE/check-up/pull/66)                                                                                                                                                                                                                                                                                                                                                                              |

---

## 4. Aprendizados e Decisões

- Manter documentação e código no mesmo repositório simplifica manutenção e aumenta a rastreabilidade.
- Checklists de review com evidências (logs/prints/saídas) elevam a qualidade e reduzem re-reviews.
- Seletores e parsing devem ser pensados para resiliência a mudanças de layout.

---

## 5. Dificuldades e Pendências

- Diferenças de ambiente dificultando reprodução de alguns cenários de scraping.
- Falta de fixtures/dados de exemplo para testes locais em certos portais.
- Acompanhar re-reviews e merges dependentes entre PRs relacionados.

---

## 6. Métricas e Evidências

- Documentação: PR#62, Issue#63
- Scrapers: PR#64 (Poder360), PR#65 (Jornal da Paraíba)
- Front-end: PR#58 (UI), PR#60 (Favoritos)
- Reviews/feedbacks: PR#21, PR#38, PR#39, PR#53, PR#64, PR#65

---

## 7. Planejamento para a Próxima Sprint

- [ ] Re-reviews e acompanhamento dos PRs até merge.
- [ ] Adicionar checklist de revisão no repositório (modelo de PR/guia de contribuição).
- [ ] Expandir cobertura: novos portais e refino dos scrapers existentes.
- [ ] Melhorias contínuas no Front-end e na documentação.
