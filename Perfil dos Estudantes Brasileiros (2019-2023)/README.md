# 🎓 Perfil dos Estudantes Brasileiros (2019–2023)

> Projeto de Análise de Dados desenvolvido utilizando SQL no Google BigQuery com dados públicos do INEP disponibilizados pela Base dos Dados.

![Status](https://img.shields.io/badge/Status-Concluído-success)
![SQL](https://img.shields.io/badge/SQL-GoogleSQL-blue)
![BigQuery](https://img.shields.io/badge/Google-BigQuery-4285F4)
![Business Intelligence](https://img.shields.io/badge/Business-Intelligence-orange)
![Open Data](https://img.shields.io/badge/Open-Data-green)

---

# 📖 Sobre o Projeto

O Brasil disponibiliza uma grande quantidade de dados educacionais por meio do Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira (INEP). Entretanto, essas informações encontram-se distribuídas em diferentes tabelas, dificultando análises integradas sobre o perfil dos estudantes brasileiros.

Este projeto teve como objetivo integrar essas bases públicas utilizando SQL no Google BigQuery para construir uma base analítica consolidada sobre os estudantes dos ensinos Fundamental, Médio e Superior entre os anos de **2019 e 2023**.

O resultado é uma base preparada para utilização em ferramentas de Business Intelligence, permitindo análises demográficas, geográficas, institucionais e de infraestrutura escolar.

---

# 🎯 Objetivos

* Integrar múltiplas bases públicas do INEP.
* Consolidar informações dos ensinos Fundamental, Médio e Superior.
* Criar indicadores analíticos para Business Intelligence.
* Desenvolver consultas SQL utilizando boas práticas de modelagem analítica.
* Produzir documentação técnica e dicionário de dados.
* Demonstrar o uso de Inteligência Artificial como apoio ao desenvolvimento de soluções analíticas.

---

# 📊 Perguntas de Negócio

A solução permite responder perguntas como:

* Qual é o perfil demográfico dos estudantes brasileiros?
* Como estão distribuídas as matrículas por estado e região?
* Como evoluíram as matrículas entre 2019 e 2023?
* Qual a participação da rede pública e privada?
* Quantos estudantes possuem deficiência?
* Qual o percentual de escolas com internet, biblioteca e laboratórios?
* Como está distribuído o ensino superior por área do conhecimento?
* Qual a participação de estudantes beneficiados por financiamento estudantil e políticas de inclusão?

---

# 🗂️ Fontes de Dados

Todas as informações utilizadas são provenientes de bases públicas oficiais.

| Fonte                      | Descrição                                              |
| -------------------------- | ------------------------------------------------------ |
| Base dos Dados             | Plataforma de acesso aos datasets públicos             |
| INEP                       | Instituto Nacional de Estudos e Pesquisas Educacionais |
| Censo Escolar              | Dados da Educação Básica                               |
| Censo da Educação Superior | Dados das Instituições de Ensino Superior              |
| IBGE                       | Diretório de Municípios                                |

---

# 🛠️ Tecnologias Utilizadas

* SQL (GoogleSQL)
* Google BigQuery
* Base dos Dados
* Git
* GitHub
* Business Intelligence
* Engenharia de Dados
* Modelagem Analítica
* Inteligência Artificial (ChatGPT)

---

# 🏗️ Arquitetura da Solução

```text
Base dos Dados
        │
        ▼
Google BigQuery
        │
        ▼
Consultas SQL
(CTEs + JOINs + Agregações)
        │
        ▼
Base Analítica Consolidada
        │
        ▼
Power BI / Dashboards
```

---

# 📚 Bases Integradas

O projeto integra informações provenientes de diferentes tabelas:

* Censo Escolar

  * Matrículas
  * Escolas

* Censo da Educação Superior

  * Cursos
  * Instituições de Ensino Superior (IES)

* Diretório Nacional de Municípios

---

# 🔍 Técnicas SQL Aplicadas

Durante o desenvolvimento foram utilizadas técnicas de SQL Analítico, incluindo:

* Common Table Expressions (CTEs)
* LEFT JOIN
* UNION ALL
* CASE WHEN
* COUNT()
* COUNTIF()
* SUM()
* SAFE_DIVIDE()
* ROUND()
* CAST()
* Agrupamentos
* Indicadores Percentuais
* Tratamento de valores nulos

---

# 📈 Indicadores Produzidos

Entre os principais indicadores gerados estão:

* Quantidade de estudantes
* Distribuição por sexo
* Distribuição por raça/cor
* Faixa etária
* Nacionalidade
* Estudantes com deficiência
* Rede pública x privada
* Infraestrutura escolar
* Internet nas escolas
* Biblioteca
* Laboratórios
* Quadra esportiva
* Financiamento estudantil
* Reserva de vagas
* Apoio social
* Mobilidade acadêmica

---

# 🤖 Uso da Inteligência Artificial

Durante o desenvolvimento do projeto foi utilizada Inteligência Artificial como ferramenta de apoio técnico.

A IA foi empregada para:

* revisão da lógica das consultas SQL;
* identificação e correção de erros de sintaxe;
* validação de JOINs;
* otimização das consultas;
* estruturação da documentação técnica;
* elaboração do dicionário de dados;
* refinamento da organização do projeto.

Todos os scripts foram testados e validados manualmente no Google BigQuery, utilizando exclusivamente dados oficiais da Base dos Dados.

---

# 📁 Estrutura do Projeto

```text
perfil-estudantes-brasileiros-2019-2023
│
├── docs/
│   ├── Projeto_Analise_Dados.md
│   ├── Dicionario_de_Dados.md
│
├── sql/
│   └── consulta_principal.sql
│
├── prompts/
│   └── Prompt_Documentacao.md
│
├── datasets/
│
├── powerbi/
│
├── images/
│
└── README.md
```

---

# 🚀 Possíveis Aplicações

A base produzida pode ser utilizada em:

* Microsoft Power BI
* Google Looker Studio
* Tableau
* Qlik Sense
* Estudos acadêmicos
* Ciência de Dados
* Business Intelligence
* Políticas Públicas
* Analytics Educacional

---

# 📌 Competências Demonstradas

* SQL Avançado
* Google BigQuery
* Integração de Dados
* Engenharia de Dados
* Business Intelligence
* Data Analytics
* ETL/ELT
* Modelagem Analítica
* Open Data
* Documentação Técnica
* Governança de Dados
* Engenharia de Prompt
* Inteligência Artificial aplicada à Análise de Dados

---

# 👨‍💻 Autor

**Marcelo dos Santos Sampaio**

Especialista em Business Intelligence | Data Analytics | Governança de Dados | Inteligência Artificial

* LinkedIn: https://linkedin.com/in/msampaioac
* GitHub: https://github.com/msampaioac

---

## ⭐ Considerações Finais

Este projeto foi desenvolvido com o propósito de consolidar conhecimentos em SQL Analítico, Engenharia de Dados e Business Intelligence utilizando dados públicos brasileiros.

Além da construção da solução analítica, o projeto evidencia boas práticas de documentação, organização, governança e utilização estratégica da Inteligência Artificial como ferramenta de apoio ao desenvolvimento, sempre com validação técnica dos resultados.
