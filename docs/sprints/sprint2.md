# 📝 Relatório de Contribuição – Sprint 2

**Disciplina:** Gestão de Configuração e Evolução de Software
**Equipe:** EH-FAKE
**Comunidade/Projeto de Software Livre:** EH-FAKE / Check-up
**Período da Sprint:** 25/09/2025 à 08/10/2025

---

## 1. Objetivos da Sprint

- [ ] Incluir novos portais de notícias no pipeline (scrapers/plays)
- [ ] Corrigir scrapers quebrados e melhorar robustez de seletores
- [ ] Validar resultados localmente e revisar dados coletados
- [ ] Manter a documentação interna atualizada

---

## 2. Entregas Coletivas

| Entrega                                                                                          | Status    | Link/Referência                                                                                                                                                                                                                                                                   | Observações                                                                                |
| :----------------------------------------------------------------------------------------------- | :-------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------- |
| Criação/Evolução de portais (Agora no Vale; Jornal de Brasília; Brasil de Fato; Agência Pública) | Parcial   | [PR#55](https://github.com/EH-FAKE/check-up/pull/55), [PR#53](https://github.com/EH-FAKE/check-up/pull/53), [Issue#50](https://github.com/EH-FAKE/check-up/issues/50), [PR#39](https://github.com/EH-FAKE/check-up/pull/39), [PR#40](https://github.com/EH-FAKE/check-up/pull/40) | Agora no Vale e Jornal de Brasília concluídos; Brasil de Fato/Agência Pública em andamento |
| Correção do scraper “Estadão”                                                                    | Concluído | [Issue#42](https://github.com/EH-FAKE/check-up/issues/42)                                                                                                                                                                                                                         |                                                                                            |
| Melhoria no Front-end (Tags populares)                                                           | Concluído | [PR#46](https://github.com/EH-FAKE/check-up/pull/46)                                                                                                                                                                                                                              |                                                                                            |
| Ajustes de CI e organização (fork do time)                                                       | Concluído | [PR#16 – fork](https://github.com/GCES-EhFake-Fork/checkUp/pull/16)                                                                                                                                                                                                               |                                                                                            |
| Atualizações na documentação interna                                                             | Concluído | [docs internos](https://gces-ehfake-fork.github.io/docs-interno/)                                                                                                                                                                                                                 |                                                                                            |

---

## 3. Contribuições Individuais

| Integrante     | Contribuições principais                                                                  | Links (PRs, Issues, Docs)                                                                                                 |
| -------------- | ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| Alana          | Implementação do portal “Agora no Vale”; Criação do relatório da sprint 2                 | [PR#55](https://github.com/EH-FAKE/check-up/pull/55)                                                                      |
| Eduardo        | Conclusão do portal “Jornal de Brasília”;                                                 | [PR#53](https://github.com/EH-FAKE/check-up/pull/53), [Issue#50](https://github.com/EH-FAKE/check-up/issues/50)           |
| Gabriel        | Correção do scraper “Estadão”                                                             | [Issue#42](https://github.com/EH-FAKE/check-up/issues/42)                                                                 |
| Felipe         | Implementação do portal “Brasil de Fato”; Testes e adequação de CI                        | [PR#39](https://github.com/EH-FAKE/check-up/pull/39), [PR#16 – fork](https://github.com/GCES-EhFake-Fork/checkUp/pull/16) |
| Pedro Silva    | Resolução de problemas na build od scraper; Documento de Política de Segurança            | [PR#44](https://github.com/EH-FAKE/check-up/pull/44), [Issue#45](https://github.com/EH-FAKE/check-up/issues/45)           |
| Vinicius       | Melhorias no Front-end                                                                    | [PR#46](https://github.com/EH-FAKE/check-up/pull/46)                                                                      |
| Mateus Levy    | Implementação do portal Poder360;                                                         | [Commit](https://github.com/GCES-EhFake-Fork/checkUp/commit/762469c5b3a75c3ef8e5c006c56e1b9ee5223716)                     |
| Ana Catarina   |                                                                                           |                                                                                                                           |
| Carlos         | Melhoria do Crawler/Scraper RBS; correção de configuração de ambiente (Playwright/Docker) | [PR#38](https://github.com/EH-FAKE/check-up/pull/38), [PR#49](https://github.com/EH-FAKE/check-up/pull/49)                |
| Daniel         |                                                                                           |                                                                                                                           |
| Luana          |                                                                                           |                                                                                                                           |
| Luciano        |                                                                                           |                                                                                                                           |
| Pedro Ferreira |                                                                                           |                                                                                                                           |
| Yago           | Início do desenvolvimento de scrapper para novo portal; estudos e ajustes de ambiente     |                                                                                                                           |

---

## 4. Dificuldades Coletivas

- Variação de estrutura HTML e seletores frágeis em alguns portais.
- Páginas com paywall (Estadão) exigindo abordagens específicas e múltiplos seletores.
- Alocação de tempo para testes manuais e validação dos resultados.

---

## 5. Aprendizados Coletivos

- Pipeline fim a fim (crawling → scraping/plays → armazenamento) mais consolidada entre o time.
- Seletores mais robustos e estratégias de fallback melhoram a resiliência a mudanças em portais.
- Importância de validações manuais e revisão cruzada via PR para garantir qualidade de dados e documentação.

---

## 6. Próximos Passos

- [ ] Acompanhar feedbacks e merges pendentes (e.g., PRs #53, #55 e correlatos).
- [ ] Iniciar novos portais priorizados e ampliar cobertura.
- [ ] Investigar automações/monitoramento para detectar quebras de scrapers.
