# Orientações

## Sobre o uso de templates no Github
No GitHub é possível criar templates personalizados para Issues e Pull Requests. Isso ajuda a padronizar as informações que os colaboradores devem incluir ao abrir as Issues e PRs em seu repositório.

### Estrutura dos templates 
Para que os templates sejam reconhecidos devemos seguir a seguinte estrutura:
- pasta de configurações do Github no projeto:
  - Para que os templates sejam reconhecidos pelo **nome_projeto/.github**
- nome da pasta de templates :
  - **nome_projeto/.github/ISSUE_TEMPLATE**
  - - **nome_projeto/.github/PULL_REQUEST_TEMPLATE**
- formato dos arquivos de template:
  - Deve ser usado formato Markdown:
    "nome_arquivo.md"

### Nomes dos modelos de ISSUE_TEMPLATE:
Os seguintes nomes de modelos são reconhecidos:
- bug_report.md
- feature_request.md

### Nomes dos modelos de PULL_REQUEST_TEMPLATE:
Os seguintes nomes de modelos são reconhecidos:
- pull_request_template.md