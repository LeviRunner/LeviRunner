<div align="center">

<img src="assets/conexoes-projetos.svg" alt="Projetos e stack tecnica" width="1200">

# Matheus Santos

**Dados & Analytics · Business Intelligence · Cloud & DevOps**

Analista de Dados com 5 anos em ambientes de producao, quatro deles em banco de dados com monitoramento de desempenho, alta disponibilidade 24/7 e integridade de base.
Atuo end-to-end: modelagem dimensional, ETL, SQL e Power BI com DAX, usando Python para automacao e tratamento — levar o dado da origem ate um painel em que o gestor confia, e sustentar o ambiente que roda por tras dele.

Sao Paulo e Regiao · hibrido ou remoto

[![DevRank](https://img.shields.io/badge/DevRank-devrank.com.br-3FB950?style=for-the-badge&logo=firefoxbrowser&logoColor=black)](https://devrank.com.br/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/matheus-santos-744417421)
[![Email](https://img.shields.io/badge/Email-Contato-F85149?style=for-the-badge&logo=microsoftoutlook&logoColor=white)](mailto:matheus.santos.m2099@outlook.com)

</div>

---

## Competencias Tecnicas

**Dados & Analytics**
`SQL avancado` • `Modelagem dimensional` • `Star schema` • `ETL` • `Power BI` • `DAX` • `Analise exploratoria` • `KPIs`

**Engenharia de Dados**
`Python` • `Polars` • `pandas` • `DuckDB` • `pandera` • `APScheduler` • `Parquet` • `Pipelines automatizados` • `Qualidade de dados`

**Bancos de Dados**
`PostgreSQL` • `MySQL` • `MongoDB` • `Redis` • `SQLite` — administracao, tuning de consultas, indexacao, backup e restauracao

**Cloud & Infraestrutura**
`Azure` • `AWS` • `GCP` • `Cloudflare` • `Terraform` • `Linux` • `Nginx`

**Containers & DevOps**
`Docker` • `Kubernetes` • `GitHub Actions` • `Ansible` • `Git` • `Prometheus` • `Grafana`

**Desenvolvimento**
`FastAPI` • `Streamlit` • `SQLAlchemy` • `TypeScript/JavaScript` • `Node.js` • `React` • `PHP`

---

## Projetos

| Projeto | Status | Descricao | Stack Principal | Link |
| --- | --- | --- | --- | --- |
| **DataLens** | Open source | Analise de dados configuravel: gera o perfil automatico de qualquer fonte (CSV, Excel, SQL, JSON, API) sem escrever codigo. Reestruturei a arquitetura para DuckDB + Polars + pandera + APScheduler sobre Parquet, saindo de um fluxo em pandas que estourava a memoria no Streamlit. | Python, DuckDB, Polars, Streamlit | [DataLens](https://github.com/LeviRunner/DataLens) |
| **DevRank** | Producao | Plataforma educacional gamificada sobre o ecossistema Cloudflare. Responsavel por toda a infraestrutura (dominio, DNS, Workers, e-mail transacional com SPF/DKIM) e pelo backend em Python, com metricas analiticas e correcao automatizada de codigo em tempo real. | Python, Next.js, Cloudflare, Resend | [devrank.com.br](https://devrank.com.br/) |
| **TechStore** | Demo | Loja ficticia de e-commerce usada como vitrine tecnica: catalogo, carrinho, checkout e area administrativa. Deploy em producao na Azure (App Service + PostgreSQL gerenciado), com pipeline de entrega continua. | Next.js, Node.js, Azure, PostgreSQL | [GitHub](https://github.com/LeviRunner) |

### DataLens em detalhe

O mesmo motor le um CSV, uma planilha Excel, um banco SQL, um JSON publico ou uma API externa: basta apontar a fonte.
Automatiza a primeira etapa de todo projeto de dados — entender o dataset — para analistas, engenheiros de dados e quem quer ver um pipeline completo e testavel.

`Config -> Conector -> Limpeza -> Perfil -> Tela + Relatorio HTML`

| Recurso | Descricao |
| --- | --- |
| Perfil automatico | Detecta tipos (numerico, data, booleano, categoria, texto), faltantes, estatisticas e distribuicoes por coluna |
| 5 conectores | CSV, Excel, SQL, JSON e API, todos sob um contrato comum e testado |
| Config hibrida | Auto-deteccao + sobrescrita por YAML + ajuste manual na tela |
| Limpeza de dados | Pipeline com log de cada transformacao aplicada |
| Painel financeiro | Ranking de ativos por excesso geometrico ajustado ao risco (Sharpe) sobre o benchmark |
| Terminal de investimentos | Cruzamento de precos (Brasil e EUA) com Selic/CDI/IPCA via API do Banco Central |
| Relatorio exportavel | Graficos interativos em Plotly e exportacao para Excel via Polars |
| Tres idiomas | Portugues, Ingles e Espanhol |

---

## Experiencia

**Los Trigales** — Analista de Dados · mai/2025 – jun/2026 · Mariano Roque Alonso, Paraguai

- Evitei US$ 14 mil na compra de um servidor ao propor uma arquitetura espelho para a segunda central: a replica sincronizou os parametros entre as unidades e absorveu a carga dos relatorios pesados, zerando os travamentos de um sistema embarcado que caia varias vezes ao dia — cerca de 5h/mes de operacao recuperadas por operador.
- Unifiquei o controle de inventario de ativos em base unica, cruzando registro de sistema e contagem fisica e tratando as divergencias.
- Estruturei a analise de compras (historico de aquisicao, comparacao de fornecedores e precos) para apoiar a decisao de reposicao.
- Otimizei o planejamento de rotas de traslado a partir de dados de carga, destino e prazo, reduzindo o tempo de carregamento.
- Automatizei relatorios recorrentes da operacao, consolidando inventario, custo de compra e desempenho de entrega.

**BunkerGames** — Assistente de Banco de Dados · jan/2021 – dez/2024 · Goiania, GO

- Sustentei alta disponibilidade 24/7 na infraestrutura de bancos de dados, com monitoramento diario de desempenho e identificacao de gargalos.
- Otimizei consultas SQL lentas e revisei indices para atender as areas de negocio, reduzindo o tempo de resposta das extracoes.
- Garanti a integridade da base com rotinas de backup e restauracao, verificacao de consistencia e acompanhamento de jobs agendados.
- Documentei e padronizei o mapeamento de tabelas e os procedimentos de rotina, reduzindo a dependencia de conhecimento individual.

**Cap Vida** — Assistente Financeiro · abr/2018 – dez/2020 · Goiania, GO

- Conciliei fluxo de caixa e movimentacao bancaria, garantindo a precisao dos registros e o cumprimento dos prazos.
- Construi planilhas de controle e relatorios periodicos que davam base as decisoes da gerencia.
- Cruzei e validei dados entre sistemas e extratos, tratando as divergencias encontradas.

---

## Formacao e Idiomas

- **Bacharelado em Ciencia da Computacao** — Estacio · 2023 – 2027
- **Formacao em Dados & Inteligencia Artificial** — DIO · jul/2026 – nov/2026 · Power BI, SQL, DAX e IA Generativa
- **Idiomas:** portugues nativo · espanhol fluente · ingles avancado

---

## Metricas

<div align="center">

<img src="metrics/stats.svg" alt="Estatisticas de contribuicao" height="170">
<img src="metrics/languages.svg" alt="Distribuicao de linguagens" height="170">

</div>
