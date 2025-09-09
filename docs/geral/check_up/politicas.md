# Políticas da comunidade

## Governança

**Modelo de governança:**

**Principais Mantenedores:**

**Processo de tomada de decisões:**

### Organização do Código
![arquitetura do projeto](https://eh-fake.github.io/docs/assets/diagrama-pipeline.png)

* **Spiders**: Web Crawlers que coletam as URL's de artigos/notícias presentes em sites de notícias e guardam esses links no banco de dados.

* **Plays**: Web Scrappers que acessam as URL's coletadas pelas Spiders e extraem o conteúdo da página.

* **Estruturação dos dados**: O conteúdo da página extraído é armazenado de forma estruturada utilizando PostgreSQL.
	* MinIO: Armazenamento de screenshots e arquivos de mídia obtidos no scrapping (descontinuado)

* **API REST**: Fornece os dados coletados por meio de requisições HTTP

* **Interface web**: Visualização dos dados em uma página web.

**ESTRUTURA DE PASTAS**

```text
check-up/
├── plays/       # Lógicas específicas de coleta
├── spiders/     # Crawlers (spiders)
├── tests/       # Testes com Pytest
├── utils/       # Funções utilitárias
├── web/
│   ├── server/  # Backend FastAPI
│   └── client/  # Frontend React
└── Makefile     # Scripts de automação
```