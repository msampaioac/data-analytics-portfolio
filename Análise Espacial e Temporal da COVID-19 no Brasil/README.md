# 🇧🇷 COVID-19 Brasil Analytics

### Engenharia de Dados, SQL Avançado, Google BigQuery e Business Intelligence

![SQL](https://img.shields.io/badge/SQL-Advanced-blue)
![BigQuery](https://img.shields.io/badge/Google-BigQuery-4285F4)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-F2C811)
![Analytics](https://img.shields.io/badge/Data-Analytics-success)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

# Sobre o Projeto

A pandemia de COVID-19 gerou um dos maiores volumes de dados públicos da história do Brasil. Informações sobre vacinação, casos, internações, óbitos, infraestrutura hospitalar, população e características demográficas passaram a ser disponibilizadas por diferentes órgãos governamentais.

Entretanto, transformar esses dados brutos em informação útil para apoiar decisões exige muito mais do que simplesmente construir dashboards. É necessário compreender modelagem de dados, integração entre bases heterogêneas, otimização de consultas, construção de métricas consistentes e aplicação de técnicas analíticas.

Este projeto foi desenvolvido justamente com esse objetivo.

Mais do que responder perguntas sobre a pandemia, este repositório demonstra competências esperadas de um profissional de Engenharia de Dados, Analytics Engineering e Business Intelligence, utilizando dados públicos disponibilizados pela Base dos Dados e processados no Google BigQuery através de SQL avançado.

---

# Objetivos

Este projeto possui quatro objetivos principais.

## 1. Demonstrar domínio de SQL

As consultas desenvolvidas exploram recursos frequentemente utilizados em ambientes corporativos, incluindo:

* Common Table Expressions (CTEs)
* Window Functions
* LEAD()
* LAG()
* RANK()
* DENSE_RANK()
* NTILE()
* SUM OVER()
* AVG OVER()
* CASE WHEN
* SAFE_DIVIDE()
* COALESCE()
* JOINS entre múltiplas tabelas
* Agregações complexas
* Cálculo de indicadores
* Otimização para BigQuery

---

## 2. Demonstrar habilidades em Engenharia de Dados

O projeto aborda conceitos fundamentais de engenharia analítica, incluindo:

* Integração de múltiplas bases públicas
* Tratamento de inconsistências
* Normalização dos dados
* Construção de camadas analíticas
* Modelagem dimensional
* Organização em Star Schema
* Criação de fatos e dimensões
* Boas práticas de organização de projetos de dados

---

## 3. Demonstrar visão analítica de negócio

Mais importante do que escrever consultas SQL é responder perguntas relevantes para o negócio.

Todas as análises foram desenvolvidas para responder questões que poderiam ser realizadas por gestores públicos, pesquisadores, analistas de saúde ou executivos responsáveis pela tomada de decisão.

---

## 4. Alimentar dashboards executivos

As consultas foram planejadas para servir como camada semântica para ferramentas de Business Intelligence, como:

* Power BI
* Tableau
* Looker Studio

---

# Fonte dos Dados

Todos os dados utilizados são públicos e foram obtidos através da plataforma Base dos Dados.

As principais fontes incluem:

* Ministério da Saúde
* OpenDataSUS
* CNES
* IBGE
* Diretórios Territoriais do Brasil

---

# Bases utilizadas

Entre as principais tabelas utilizadas estão:

* Vacinação COVID-19
* Casos Graves (SRAG)
* Infraestrutura Hospitalar (CNES)
* População por Município
* População por Faixa Etária
* Diretório de Municípios
* Informações territoriais

---

# Problema de Negócio

Durante a pandemia diversos gestores precisavam responder perguntas como:

* Onde a vacinação está avançando mais rapidamente?
* Quais municípios apresentam maior risco?
* Existe relação entre vacinação e mortalidade?
* A infraestrutura hospitalar foi suficiente?
* Quais regiões sofreram maior pressão sobre o sistema de saúde?
* Quais grupos populacionais apresentaram menor cobertura vacinal?

Responder essas perguntas exige integração entre diversas bases de dados.

Este projeto demonstra exatamente esse processo.

---

# Perguntas Analíticas Respondidas

## Vacinação

* Como evoluiu a vacinação ao longo do tempo?
* Quais estados vacinaram mais rapidamente?
* Qual a cobertura vacinal por município?
* Qual a cobertura por região?
* Como evoluiu a vacinação por faixa etária?
* Qual a evolução da aplicação das doses de reforço?

---

## Mortalidade

* Qual a taxa de mortalidade por município?
* Quais regiões apresentaram maior letalidade?
* Como evoluíram os óbitos durante a pandemia?
* Existem diferenças entre estados?

---

## Infraestrutura Hospitalar

* Quantos leitos existem por município?
* Qual a disponibilidade de leitos por habitante?
* Existe correlação entre quantidade de leitos e mortalidade?
* Quais municípios sofreram maior pressão hospitalar?

---

## Indicadores Demográficos

* Como a população influencia os indicadores?
* Qual a vacinação proporcional à população?
* Quais grupos etários apresentaram maior cobertura?
* Quais grupos ficaram abaixo da média nacional?

---

## Inteligência Territorial

* Comparação entre regiões brasileiras
* Ranking de municípios
* Ranking de estados
* Evolução temporal
* Mapas de calor
* Indicadores regionais

---

# Arquitetura do Projeto

```
                Base dos Dados
                       │
                       │
              Google BigQuery
                       │
         Limpeza e Transformações SQL
                       │
          Views Analíticas (Camada Gold)
                       │
           Modelo Dimensional (Star Schema)
                       │
             Power BI / Tableau
                       │
           Dashboards e Indicadores
```

---

# Estrutura do Repositório

```
covid19-brasil-sql-bi/

├── README.md
├── sql/
├── docs/
├── modelagem/
├── powerbi/
├── assets/
└── LICENSE
```

---

# Competências Demonstradas

## Engenharia de Dados

* SQL Avançado
* Google BigQuery
* Data Warehouse
* Modelagem Dimensional
* ETL/ELT
* Integração de Dados
* Qualidade de Dados
* Analytics Engineering

---

## Business Intelligence

* Modelagem para Power BI
* Construção de KPIs
* Storytelling com Dados
* Dashboards Executivos
* Indicadores Estratégicos
* Visualização de Dados

---

## Analytics

* Estatística Descritiva
* Indicadores Epidemiológicos
* Séries Temporais
* Rankings
* Comparações Regionais
* Correlações
* Análise Exploratória

---

# Tecnologias Utilizadas

* Google BigQuery
* SQL
* Base dos Dados
* Power BI
* Git
* GitHub

---

# Próximos Passos

As próximas evoluções previstas para este projeto incluem:

* Construção de um pipeline automatizado de ingestão de dados.
* Criação de uma camada Silver e Gold seguindo arquitetura Medallion.
* Implementação de testes de qualidade dos dados.
* Desenvolvimento de dashboards interativos no Power BI.
* Publicação de um Data Dictionary completo.
* Criação de métricas padronizadas para consumo por ferramentas de BI.
* Estudos de desempenho e otimização de consultas no BigQuery.
* Inclusão de análises estatísticas e modelos preditivos.

---

# Autor

**Marcelo Sampaio**

Especialista em Business Intelligence • Analytics • Engenharia de Dados

GitHub: https://github.com/msampaioac

---

## Licença

Este projeto está licenciado sob a licença MIT e tem finalidade educacional e demonstrativa, utilizando exclusivamente dados públicos disponibilizados por órgãos governamentais brasileiros.
