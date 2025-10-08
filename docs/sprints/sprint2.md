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

| Entrega                                                 | Status (Concluído/Parcial/Pendente) | Link/Referência                                                                                                 | Observações                  |
| ------------------------------------------------------- | ----------------------------------- | --------------------------------------------------------------------------------------------------------------- | ---------------------------- |
| Novo portal “Agora no Vale” integrado                   | Concluído                           | [PR#55](https://github.com/EH-FAKE/check-up/pull/55)                                                            |                              |
| Play do “Jornal de Brasília” finalizada                 | Concluído                           | [PR#53](https://github.com/EH-FAKE/check-up/pull/53), [Issue#50](https://github.com/EH-FAKE/check-up/issues/50) |                              |
| Correção do scraper “Estadão”                           | Parcial                             | [Issue#42](https://github.com/EH-FAKE/check-up/issues/42)                                                       | Ajustes/PR em acompanhamento |
| Evoluções em scrapers (Brasil de Fato, Agência Pública) | Parcial                             | [PR#39](https://github.com/EH-FAKE/check-up/pull/39), [PR#40](https://github.com/EH-FAKE/check-up/pull/40)      | Iterações contínuas          |
| Melhoria no Front-end (Tags populares)                  | Concluído                           | [PR#46](https://github.com/EH-FAKE/check-up/pull/46)                                                            |                              |
| Ajustes de CI e organização (fork do time)              | Concluído                           | [PR#16 – fork](https://github.com/GCES-EhFake-Fork/checkUp/pull/16)                                             |                              |
| Atualizações na documentação interna                    | Concluído                           | [docs internos](https://gces-ehfake-fork.github.io/docs-interno/)                                               |                              |

---

## 3. Contribuições Individuais

| Integrante     | Contribuições principais                                                       | Links (PRs, Issues, Docs)                                                                                                 |
| -------------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------- |
| Alana          | Implementação do portal “Agora no Vale”; Criação do relatório da sprint 2      | [PR#55](https://github.com/EH-FAKE/check-up/pull/55)                                                                      |
| Eduardo        | Conclusão do portal “Jornal de Brasília”;                                      | [PR#53](https://github.com/EH-FAKE/check-up/pull/53), [Issue#50](https://github.com/EH-FAKE/check-up/issues/50)           |
| Gabriel        | Correção do scraper “Estadão”                                                  | [Issue#42](https://github.com/EH-FAKE/check-up/issues/42)                                                                 |
| Felipe         | Implementação do portal “Brasil de Fato”; Testes e adequação de CI             | [PR#39](https://github.com/EH-FAKE/check-up/pull/39), [PR#16 – fork](https://github.com/GCES-EhFake-Fork/checkUp/pull/16) |
| Pedro Silva    | Resolução de problemas na build od scraper; Documento de Política de Segurança | [PR#44](https://github.com/EH-FAKE/check-up/pull/44), [Issue#45](https://github.com/EH-FAKE/check-up/issues/45)           |
| Vinicius       | Melhorias no Front-end                                                         | [PR#46](https://github.com/EH-FAKE/check-up/pull/46)                                                                      |
| Ana Catarina   |                                                                                |                                                                                                                           |
| Carlos         |                                                                                |                                                                                                                           |
| Daniel         |                                                                                |                                                                                                                           |
| Luana          |                                                                                |                                                                                                                           |
| Luciano        |                                                                                |                                                                                                                           |
| Pedro Ferreira |                                                                                |                                                                                                                           |
| Yago           |                                                                                |                                                                                                                           |

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
- [ ] Endereçar a abertura de PR para a correção do Estadão e outras priorizadas.
- [ ] Iniciar novos portais priorizados e ampliar cobertura.
- [ ] Investigar automações/monitoramento para detectar quebras de scrapers.
