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

- [x] Finalizar e abrir o PR referente à issue #30 no repositório original.
- [ ] Acompanhar o feedback da comunidade/mantenedores sobre a contribuição.
- [x] Buscar uma nova oportunidade de contribuição, de preferência no código (scrapers ou testes).
- [x] Aprofundar entendimento das migrations e arquitetura do banco de dados do projeto.

## Sprint 2 – 25/09 - 02/10

### Resumo da Sprint

Nesta sprint o foco foi na **análise técnica aprofundada** dos repositórios do projeto e **correção de scrapers quebrados**. Após a contribuição inicial com documentação, avancei para um trabalho mais técnico de análise da arquitetura do sistema check-up e identificação de problemas nos scrapers de portais de notícias. O trabalho culminou na **correção completa do scraper do portal Estadão**, incluindo análise de problemas, desenvolvimento da solução e documentação técnica detalhada.

### Atividades Realizadas

| Data       | Atividade                                                                   | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                                                                          | Status    |
| ---------- | --------------------------------------------------------------------------- | --------------------------------- | ---------------------------------------------------------------------------------------- | --------- |
| 25/09/2025 | Análise técnica dos 3 repositórios principais (check-up, docs, airflow-rag) | Estudo/Doc                        | [Análise Repositórios](repositórios analisados)                                          | Concluído |
| 26/09/2025 | Identificação de 5 portais problemáticos e priorização de correções         | Análise                           | Brasil de Fato, RBS, Terra, Globo, Estadão                                               | Concluído |
| 30/09/2025 | Análise detalhada da estrutura HTML do portal Estadão                       | Estudo/Código                     | Inspeção de https://www.estadao.com.br                                                   | Concluído |
| 01/10/2025 | Re-inspeção de páginas individuais de notícias do Estadão                   | Estudo/Código                     | Análise de estrutura de artigos, paywall e seletores                                     | Concluído |
| 01/10/2025 | Desenvolvimento da correção completa do spider Estadão                      | Código                            | [Spider Atualizado](https://github.com/EH-FAKE/check-up/blob/develop/spiders/estadao.py) | Concluído |
| 01/10/2025 | Criação de issue técnica completa seguindo padrão                           | Doc                               | [Issue Estadão](https://github.com/EH-FAKE/check-up/issues/42)                           | Concluído |

### Maiores Avanços

- **Análise arquitetural completa**: Compreendi a estrutura completa do sistema
- **Diagnóstico preciso**: Identifiquei que 8 portais estão funcionais e 5 problemáticos
- **Solução técnica robusta**: Desenvolvi correção completa do Estadão com múltiplos seletores, tratamento de paywall e filtragem inteligente

### Maiores Dificuldades

- **Complexidade do paywall**: O Estadão tem muito conteúdo restrito para assinantes, exigindo estratégias de extração parcial
- **Seletores CSS voláteis**: A estrutura HTML moderna do portal muda frequentemente, necessitando múltiplos seletores de fallback

### Aprendizados

- **Arquitetura de sistemas de scraping**: Compreendi como funciona a pipeline completa desde coleta de URLs até visualização no frontend
- **Técnicas avançadas de web scraping**: Aprendi sobre tratamento de paywalls, múltiplos seletores, rate limiting e detecção de bot
- **Playwright vs Scrapy**: Entendi quando usar cada ferramenta
- **Análise de priorização técnica**: Aprendi a criar matrizes de decisão para correções em projetos reais

### Plano Pessoal para a Próxima Sprint

- [x] **Melhorar a correção do Estadão** no ambiente de desenvolvimento
- [x] **Testar e validar** a solução com as métricas definidas (70%+ taxa de extração)
- [x] **Fechar o PR** com a correção do Estadão no repositório original
- [x] **Iniciar correção do próximo portal**
- [x] **Contribuir com melhorias** no sistema de monitoramento de scrapers quebrados
- [x] **Documentar processo** de manutenção preventiva para evitar quebras futuras

## Sprint 3 – 13/10 - 22/10/

### Resumo da Sprint

Nesta sprint, o foco principal foi a implementação das oportunidades de melhoria identificadas nas sprints anteriores, especialmente no que diz respeito à confiabilidade e manutenibilidade do projeto Check Up. Foram implementados dois sistemas críticos: o sistema de monitoramento e alertas para os scrapers, visando a detecção automática de falhas e degradação da saúde dos scrapers em execução; e um sistema de versionamento e gestão de seletores CSS, para oferecer histórico, fallback automático e maior resiliência diante das frequentes mudanças nas páginas web que são alvo do scraping.

Essas implementações representam um avanço significativo para a Engenharia e Gerência de Configuração do projeto, melhorando tanto a capacidade de operação contínua quanto o controle sobre mudanças e recuperação rápida em caso de falhas.

---

### Atividades Realizadas

| Data       | Atividade                                                               | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                             | Status    |
| ---------- | ----------------------------------------------------------------------- | --------------------------------- | ------------------------------------------- | --------- |
| 03/11/2025 | Implementação do módulo de monitoramento e alertas dos scrapers         | Código                            | https://github.com/EH-FAKE/check-up/pull/84 | Concluído |
| 06/11/2025 | Integração do sistema de alertas com Slack para notificações            | Código                            | https://github.com/EH-FAKE/check-up/pull/84 | Concluído |
| 08/11/2025 | Desenvolvimento do módulo de versionamento e histórico de seletores CSS | Código                            | https://github.com/EH-FAKE/check-up/pull/84 | Concluído |
| 12/11/2025 | Integração do versionamento de seletores com os spiders do Scrapy       | Código                            | https://github.com/EH-FAKE/check-up/pull/84 | Concluído |
| 14/11/2025 | Testes manuais e correções iniciais dos módulos implementados           | Testes                            | https://github.com/EH-FAKE/check-up/pull/84 | Concluído |
| 16/11/2025 | Documentação técnica dos novos sistemas no repositório                  | Documentação                      | https://github.com/EH-FAKE/check-up/pull/84 | Concluído |

---

### Maiores Avanços

- Implementação completa do sistema de monitoramento para saúde dos scrapers com métricas detalhadas e alertas automáticos via Slack.
- Desenvolvimento de um mecanismo robusto de versionamento para seletores CSS, permitindo histórico, fallback automático e marcação de seletores quebrados.
- Melhoria significativa da resiliência dos scrapers, facilitando manutenção e prevenindo falhas silenciosas.
- Integração dos novos sistemas com as pipelines existentes, garantindo mínimo impacto para o fluxo atual.
- Documentação clara e organizada que facilita a contribuição e entendimento futuro da equipe e da comunidade.

---

### Maiores Dificuldades

- Ajustar a integração do sistema de alertas ao ambiente do projeto com restrições de permissões e configurações de canais.
- Garantir a compatibilidade do versionamento dos seletores com spiders já existentes, sobretudo no uso do Scrapy e suas formas de extração.
- Adaptar os testes manuais para verificar casos onde o fallback automático dos seletores é necessário, dada a variabilidade das páginas.
- Gerenciar o tempo para documentar todas as etapas da implementação e garantir padrões consistentes.

---

### Aprendizados

- Compreendi melhor o valor de sistemas de monitoramento pró-ativos em projetos de scraping, especialmente diante de portais web dinâmicos.
- Validei técnicas eficazes de versionamento e fallback de CSS selectors como forma prática de melhorar estabilidade.
- Aprendi a integrar serviços externos de alertas (Slack) para garantir comunicação imediata da equipe frente a falhas.
- Entendi a importância de documentação contínua para garantir que novas implementações sejam acessíveis a novos contribuidores.
- Reforcei conhecimentos sobre testes focados em variabilidade de fontes externas e comportamento dinâmico de páginas web.

---

### Plano Pessoal para a Próxima Sprint

- [ ] Realizar testes automatizados e de carga para validar o monitoramento em ambientes de produção simulados.
- [ ] Planejar e iniciar a implementação do sistema de rate limiting inteligente e circuit breaker para os scrapers.
- [ ] Concluir integração do versionamento de seletores com outras fontes além do Estadão.
- [ ] Trabalhar na automatização dos testes para os spiders, com foco em evitar regressões.
- [ ] Monitorar feedback dos mantenedores após submissão de PRs referentes às melhorias implementadas.
- [ ] Continuar documentação do processo e melhoria da governança na equipe e comunidade.

## Sprint 4 – 18/11 - 19/11

### Resumo da Sprint

Nesta sprint o foco principal foi a implementação completa do middleware para rate limiting inteligente e circuit breaker no sistema de scrapers do projeto Check Up, com o objetivo de evitar bloqueios de IP e detectar de forma rápida quando os portais monitorados estão restringindo o acesso. Essa camada intermediária (middleware) foi integrada à pipeline dos scrapers, garantindo maior resiliência, redução de erros causados por bloqueios e melhora na estabilidade das execuções.

A implementação foi feita conforme especificado na issue #85 e submetida via Pull Request #86. Essa etapa representa um avanço substancial nas práticas de engenharia e operação do sistema, evitando falhas silenciosas e otimizando a utilização dos recursos de rede.


### Atividades Realizadas

| Data       | Atividade                                           | Tipo (Código/Doc/Discussão/Outro) | Link/Referência                                                                                          | Status    |
| ---------- | --------------------------------------------------- | --------------------------------- | -------------------------------------------------------------------------------------------------------- | --------- |
| 18/11/2025 | Implementação do middleware de rate limiting e circuit breaker | Código                            | [Pull Request #86](https://github.com/EH-FAKE/check-up/pull/86)                                          | Concluído |
| 19/11/2025 | Integração do middleware com pipeline dos scrapers | Código                            | [Pull Request #86](https://github.com/EH-FAKE/check-up/pull/86)                                          | Concluído |
| 19/11/2025 | Testes iniciais da funcionalidade e correções       | Testes                            | Interno                                                                                                | Concluído |
| 19/11/2025 | Atualização da documentação do middleware            | Documentação                      | Incluída no repositório conforme PR e comentários                                                       | Concluído |


### Maiores Avanços

- Middleware eficiente para controle fino de requisições, evitando bloqueios por excesso de chamadas (rate limiting).  
- Circuit breaker que detecta padrões de falhas em portais, interrompendo requisições temporariamente para evitar banimento.  
- Integração transparente com o framework Scrapy, utilizando middlewares personalizados para monitorar e controlar requisições HTTP.  
- Código limpo e documentado, seguindo padrão do repositório e práticas recomendadas para contribuição.  
- Melhoria da robustez e resiliência do sistema, diminuindo erros operacionais causados por limitações externas.


### Maiores Dificuldades

- Ajustes para balancear tolerância do circuito e tempo de recuperação, evitando tanto bloqueios prematuros quanto exposição a falhas prolongadas.  
- Validação e testes para garantir que a limitação não prejudique a coleta de dados, mantendo boa performance.  
- Entendimento da arquitetura interna para integrar o middleware ao ciclo do Scrapy sem impactar outros componentes.


### Aprendizados

- Importância da aplicação de circuit breaker para evitar cascatas e melhorar a estabilidade em sistemas que dependem de terceiros.  
- Melhores práticas em implementação de rate limiting para scrapers em ambientes reais, balanceando restrição e produtividade.  
- Processo de revisão de código colaborativa via pull requests, fortalecendo a governança e qualidade do software.  
- Valor de documentação detalhada para facilitar manutenção e onboarding de novos colaboradores.


### Plano Pessoal para a Próxima Sprint

- [ ] Planejar e iniciar implementação da suite de testes automatizados para middleware e scrapers.  
- [ ] Expandir cobertura dos testes para os scrapers recém-adaptados para versões mais resilientes.  
- [ ] Acompanhar feedback dos mantenedores e comunidade para validar e potencialmente otimizar o middleware implementado.  
- [ ] Continuar aprimorando documentação de arquitetura e operação do projeto para facilitar contribuições futuras.  
- [ ] Investigar automações para monitoramento em tempo real da saúde dos scrapers integrando o middleware.
