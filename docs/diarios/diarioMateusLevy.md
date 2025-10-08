# Diário de Bordo – Mateus Levy

**Disciplina:** Gerência e Configuração de Software

**Equipe:** WebScrapping

**Comunidade/Projeto de Software Livre:** Check-up

---

## Sprint 2 – 25/09 - 08/10 

### Resumo da Sprint

Nesta sprint, o foco foi a expansão da cobertura de portais de notícias do projeto, com o desenvolvimento de um novo scraper para o site Poder360. O trabalho foi dividido em duas frentes: a criação de um spider para a coleta de URLs de notícias e um play para a extração do conteúdo dessas páginas.

### Atividades Realizadas

| Data       | Atividade                                     | Tipo (Código/Doc/Discussão/Outro) | Link/Referência | Status    |
| ---------- | --------------------------------------------- | --------------------------------- | --------------- | --------- |
| 07/10/2025 | Desenvolvimento do Spider para o Poder360     | Código                            | [Commit](https://github.com/GCES-EhFake-Fork/checkUp/commit/762469c5b3a75c3ef8e5c006c56e1b9ee5223716)  | Concluído |

### Maiores Avanços

- Implementação do fluxo completo de scraping (spider + play) para o portal Poder360.
- Criação de uma lógica de filtragem de URLs no spider para coletar apenas links de notícias, ignorando seções institucionais e outras.
- Extração de dados estruturados (título, subtítulo, corpo e tags) das páginas de artigos.

### Maiores Dificuldades

- Identificar seletores CSS que fossem específicos o suficiente para os dados desejados, mas robustos a pequenas alterações no layout do site.
- Realizar a limpeza do conteúdo extraído do corpo da notícia, removendo elementos como anúncios e chamadas para newsletter.

### Aprendizados

- Aplicação prática da combinação do Scrapy (para crawling e descoberta de links) e Playwright (para renderização de páginas e extração de conteúdo).
- Técnicas para inspecionar e filtrar URLs com base em sua estrutura para otimizar a coleta.

### Plano Pessoal para a Próxima Sprint

- [ ] Submeter os Pull Requests com as implementações do portal Poder360.
- [ ] Acompanhar o processo de code review e aplicar os feedbacks necessários.
- [ ] Iniciar a análise do próximo portal de notícias a ser implementado.