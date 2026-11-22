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

## Publicações & Estudos de Caso

Artigos autorais no [Medium](https://medium.com/@enosbarros):

- [Como transformar dados operacionais do Salesforce em uma plataforma pronta para Analytics e IA](https://medium.com/@enosbarros/arquitetura-de-dados-transformando-informa%C3%A7%C3%B5es-do-salesforce-em-estrat%C3%A9gia-de-neg%C3%B3cios-7e14506f957a) — arquitetura em camadas para preparar dados operacionais para análises, indicadores e modelos preditivos.
- [Quando os dados mostraram que estávamos ouvindo poucas pessoas](https://medium.com/@enosbarros/quando-os-dados-mostraram-que-est%C3%A1vamos-ouvindo-poucas-pessoas-ad5699784c74) — análise estatística que ampliou em mais de 140 clientes/mês a população elegível para pesquisas NPS.
- [Automação inteligente de sorteio para NPS relacional](https://medium.com/@enosbarros/automa%C3%A7%C3%A3o-inteligente-de-sorteio-para-nps-relacional-19e457d1e161) — automação que reduziu 6 horas de trabalho manual para 1 clique.
- [Estudo de caso Zaitt: um mercado sem atendentes nem filas no Brasil](https://medium.com/@enosbarros/estudo-de-caso-zaitt-6947b25896d1) — estudo de caso de produto e experiência.
- [Rest in Plate](https://medium.com/@enosbarros/rest-in-plate-bac8a64cd357) — estudo de caso sobre espera e filas.
- [Desafio Study the Sun](https://medium.com/@enosbarros/desafio-study-the-sun-ff50a669c14d) — estudo de caso de UX.

---

## Stack

- **Linguagens:** Python, SQL, PowerShell, Bash
- **Cloud:** Azure (Functions, App Service, SQL Database, AI Search, OpenAI, ACR), GCP
- **Dados & IA:** RAG, LLMs (OpenAI/Gemini), ChromaDB, Databricks (arquitetura Medallion), scikit-learn, Pandas
- **Infra & DevOps:** Docker, Terraform, Bicep, GitHub Actions, Azure CLI, Git

## Contato

- E-mail: enosbarros@gmail.com
- Medium: [medium.com/@enosbarros](https://medium.com/@enosbarros)
