# É Fake

Esse repositório é destinado a centralizar todas as entregas do projeto É Fake da disciplina de Gerência e Configuração de Software (GCES) do semestre 2.2025.


## Desenvolvimento Local

### Pré-requisitos

- Python 3.8 ou superior
- Git

### Instalação e Execução

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/GCES-EhFake-Fork/docs-interno.git
   cd docs-interno
   ```

2. **Crie um ambiente virtual:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # no Windows: venv\Scripts\activate
   ```

3. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Execute localmente:**
   ```bash
   mkdocs serve
   ```

5. **Acesse no navegador:**
   Visite `http://localhost:8000`

## 🚀 Deploy

O site é tem deploy automático no GitHub Pages quando as alterações são enviadas para a branch principal (main) usando o GitHub Actions.

### Deploy Manual

Se desejar fazer deploy manualmente, execute:

```bash
mkdocs gh-deploy
```