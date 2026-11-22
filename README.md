# Enos de Barros Cruz

**Cloud & AI Solutions** · FIAP (RM 561926)

Construo soluções de dados e IA aplicada com foco em nuvem: arquitetura de agentes,
RAG, pipelines analíticos e infraestrutura como código.

---

## Projetos em destaque

### [ia-kam](https://github.com/Enoscruz/ia-kam)
Copiloto de análise operacional para incidentes e KPI, com interface em Streamlit e fluxo multi-agente.

- Orquestrador com roteamento de intenção e agentes de Consulta (SQL read-only), RAG e Analytics
- Recuperação contextual com índice vetorial local (Chroma) ou Azure AI Search
- Camada de LLM multi-provedor: OpenAI, Gemini ou mock
- Controle de acesso por e-mail, painel de governança e trilha de auditoria
- Empacotamento em Docker e deploy automatizado no Azure App Service

`Python` · `Streamlit` · `RAG` · `Azure OpenAI` · `Azure AI Search` · `Azure SQL` · `Docker`

### [AzureQueimadasINPE](https://github.com/Enoscruz/AzureQueimadasINPE-rm561926)
Coleta de focos de queimadas (INPE) com infraestrutura provisionada como código.

- Azure Functions (HTTP trigger) em Python e persistência em MySQL Flexible Server
- Infraestrutura com Terraform (AzureRM)
- CI/CD com GitHub Actions: `terraform plan` em PR e `apply` na `main`, além de workflow manual de destroy

`Python` · `Azure Functions` · `Terraform` · `MySQL` · `GitHub Actions`

### [el-nino](https://github.com/Enoscruz/el-nino)
Agente conversacional offline e relatório analítico sobre o El Niño com dados do INMET (2024–2026).

- Análise de anomalias por estação e resumos nacional e por UF
- Empacotamento em Docker e pipelines em GitHub Actions
- Infraestrutura descrita em Bicep

`Python` · `Bicep` · `GitHub Actions` · `Docker`

---

## Stack

- **Linguagens:** Python, SQL, PowerShell, Bash
- **Cloud:** Azure (Functions, App Service, SQL Database, AI Search, OpenAI, ACR), GCP
- **Dados & IA:** RAG, LLMs (OpenAI/Gemini), ChromaDB, Databricks (arquitetura Medallion), scikit-learn, Pandas
- **Infra & DevOps:** Docker, Terraform, Bicep, GitHub Actions, Azure CLI, Git

## Contato

- E-mail: enosbarros@gmail.com
