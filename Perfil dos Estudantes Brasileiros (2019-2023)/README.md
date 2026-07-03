# 🎓 Perfil dos Estudantes Brasileiros (2015–2024)

> Projeto de Engenharia de Dados e Análise de Dados desenvolvido utilizando SQL no Google BigQuery com dados públicos do INEP disponibilizados pela Base dos Dados.

![Status](https://img.shields.io/badge/Status-Concluído-success)
![SQL](https://img.shields.io/badge/SQL-GoogleSQL-blue)
![BigQuery](https://img.shields.io/badge/Google-BigQuery-4285F4)
![Business Intelligence](https://img.shields.io/badge/Business-Intelligence-orange)
![Data Engineering](https://img.shields.io/badge/Data-Engineering-purple)
![Open Data](https://img.shields.io/badge/Open-Data-green)

---

# 📖 Sobre o Projeto

O Brasil disponibiliza um vasto volume de dados educacionais por meio do Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira (INEP). Entretanto, essas informações encontram-se distribuídas em diferentes bases, níveis de ensino e estruturas de dados, dificultando análises integradas sobre o perfil dos estudantes brasileiros.

Este projeto foi desenvolvido para integrar e transformar essas bases públicas utilizando SQL no Google BigQuery, construindo uma camada analítica consolidada contendo informações da Educação Básica e do Ensino Superior no período de **2015 a 2024**.

A solução aplica conceitos de Engenharia de Dados, Modelagem Analítica e Business Intelligence para disponibilizar uma base consistente, documentada e preparada para consumo em ferramentas analíticas, permitindo estudos demográficos, geográficos, institucionais, socioeconômicos e de infraestrutura educacional.

Além da construção da base analítica, o projeto demonstra boas práticas de documentação técnica, organização de repositório, padronização de consultas SQL e utilização de Inteligência Artificial como ferramenta de apoio ao desenvolvimento.

---

# 🎯 Objetivos

- Integrar múltiplas bases públicas do INEP em uma única camada analítica.
- Consolidar informações da Educação Básica e do Ensino Superior.
- Aplicar técnicas de transformação e integração de dados utilizando SQL no Google BigQuery.
- Construir uma base preparada para consumo em ferramentas de Business Intelligence.
- Demonstrar boas práticas de Engenharia de Dados, Modelagem Analítica e Governança de Dados.
- Produzir documentação técnica completa, incluindo dicionário de dados e especificações do projeto.
- Demonstrar o uso responsável da Inteligência Artificial como apoio ao desenvolvimento de soluções analíticas.

---

# 📊 Perguntas de Negócio

A solução permite responder perguntas como:

- Qual é o perfil demográfico dos estudantes brasileiros?
- Como estão distribuídas as matrículas por estado e região?
- Como evoluíram as matrículas entre **2015 e 2024**?
- Qual a participação da rede pública e privada?
- Quantos estudantes possuem deficiência?
- Qual o percentual de escolas com acesso à internet?
- Como evoluiu a infraestrutura das escolas brasileiras?
- Qual a disponibilidade de bibliotecas, laboratórios e quadras esportivas?
- Como está distribuído o ensino superior por área do conhecimento?
- Qual a participação de estudantes beneficiados por financiamento estudantil?
- Como evoluíram os indicadores de inclusão educacional ao longo dos anos?

---

# 🗂️ Fontes de Dados

Todas as informações utilizadas são provenientes de bases públicas oficiais.

| Fonte | Descrição |
|--------|-----------|
| Base dos Dados | Plataforma de acesso aos datasets públicos brasileiros |
| INEP | Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira |
| Censo Escolar | Dados da Educação Básica |
| Censo da Educação Superior | Dados das Instituições de Ensino Superior |
| IBGE | Diretório Nacional de Municípios |

---

# 🛠️ Tecnologias Utilizadas

- SQL (GoogleSQL)
- Google BigQuery
- Base dos Dados
- Git
- GitHub
- Business Intelligence
- Engenharia de Dados
- Modelagem Analítica
- ETL / ELT
- Open Data
- Inteligência Artificial (ChatGPT)

---

# 🏗️ Arquitetura da Solução

```text
             Dados Públicos
      (Base dos Dados / INEP)
                    │
                    ▼
           Google BigQuery
                    │
                    ▼
 Extração • Integração • Transformação
    (SQL • CTEs • JOINs • Agregações)
                    │
                    ▼
      Camada Analítica Consolidada
                    │
                    ▼
 Business Intelligence e Dashboards
   (Power BI • Looker Studio • Qlik)
```

---

# 📚 Bases Integradas

O projeto integra informações provenientes de diferentes bases públicas:

### Educação Básica

- Matrículas
- Escolas

### Educação Superior

- Cursos
- Instituições de Ensino Superior (IES)

### Dados Geográficos

- Estados
- Municípios
- Regiões

---

# 🔍 Técnicas SQL Aplicadas

Durante o desenvolvimento foram utilizadas técnicas de SQL Analítico, incluindo:

- Common Table Expressions (CTEs)
- LEFT JOIN
- INNER JOIN
- UNION ALL
- CASE WHEN
- COUNT()
- COUNTIF()
- SUM()
- AVG()
- ROUND()
- SAFE_DIVIDE()
- CAST()
- COALESCE()
- Window Functions
- Agregações
- Indicadores Percentuais
- Tratamento de valores nulos
- Padronização de atributos

---

# 📈 Indicadores Produzidos

Entre os principais indicadores gerados estão:

## Perfil dos Estudantes

- Quantidade de estudantes
- Distribuição por sexo
- Distribuição por raça/cor
- Faixa etária
- Nacionalidade
- Estudantes com deficiência

## Indicadores Educacionais

- Matrículas por modalidade
- Matrículas por etapa de ensino
- Rede pública x privada
- Evolução anual das matrículas

## Infraestrutura Escolar

- Internet
- Biblioteca
- Laboratórios
- Quadra esportiva
- Equipamentos tecnológicos

## Ensino Superior

- Cursos ofertados
- Instituições de Ensino Superior
- Financiamento estudantil
- Reserva de vagas
- Apoio social
- Mobilidade acadêmica

---

# 🤖 Uso da Inteligência Artificial

Durante o desenvolvimento do projeto foi utilizada Inteligência Artificial exclusivamente como ferramenta de apoio técnico.

A IA auxiliou em atividades como:

- revisão da lógica das consultas SQL;
- identificação e correção de erros de sintaxe;
- validação de JOINs;
- otimização das consultas;
- revisão da modelagem analítica;
- elaboração da documentação técnica;
- construção do dicionário de dados;
- organização do repositório;
- refinamento das especificações funcionais.

Todas as consultas SQL foram desenvolvidas, testadas e validadas manualmente no Google BigQuery utilizando exclusivamente dados públicos oficiais disponibilizados pela Base dos Dados.

---

# 📁 Estrutura do Projeto

```text
perfil-estudantes-brasileiros-2015-2024
│
├── README.md
│
├── docs/
│   ├── Projeto_Analise_Dados.md
│   ├── Dicionario_de_Dados.md
│   ├── Especificacao_Dashboard.md
│   └── Arquitetura.md
│
├── sql/
│   ├── consulta_principal.sql
│   ├── views.sql
│   └── consultas_auxiliares.sql
│
├── prompts/
│   └── Prompt_Documentacao.md
│
├── datasets/
│
├── notebooks/
│
├── powerbi/
│
├── images/
│
└── LICENSE
```

---

# 🚀 Possíveis Aplicações

A base produzida pode ser utilizada em:

- Microsoft Power BI
- Google Looker Studio
- Tableau
- Qlik Sense
- Estudos Acadêmicos
- Ciência de Dados
- Engenharia de Dados
- Business Intelligence
- Analytics Educacional
- Avaliação de Políticas Públicas
- Apoio à Tomada de Decisão

---

# 💼 Competências Demonstradas

Este projeto evidencia competências práticas nas seguintes áreas:

- Engenharia de Dados
- SQL (GoogleSQL)
- Google BigQuery
- Integração de Dados
- ETL / ELT
- Modelagem Analítica
- Business Intelligence
- Data Analytics
- Open Data
- Governança de Dados
- Documentação Técnica
- Versionamento com Git
- Engenharia de Prompt
- Inteligência Artificial aplicada à Engenharia de Dados

---

# 📖 Documentação

A documentação do projeto contempla:

- Descrição da solução
- Arquitetura analítica
- Dicionário de Dados
- Especificação do Dashboard
- Consultas SQL
- Organização do repositório
- Regras de negócio
- Fontes oficiais dos dados

---

# 👨‍💻 Autor

**Marcelo dos Santos Sampaio**

Especialista em Business Intelligence | Data Analytics | Engenharia de Dados | Governança de Dados | Inteligência Artificial

- **LinkedIn:** https://linkedin.com/in/msampaioac
- **GitHub:** https://github.com/msampaioac/data-analytics-portfolio

---

# ⭐ Considerações Finais

Este projeto foi desenvolvido com o objetivo de demonstrar competências práticas em Engenharia de Dados, SQL Analítico e Business Intelligence utilizando dados públicos brasileiros disponibilizados pelo INEP por meio da plataforma Base dos Dados.

A solução integra diferentes bases educacionais em uma estrutura analítica consolidada, evidenciando boas práticas de integração, transformação e documentação de dados, além de organização de projetos em ambiente Git.

Mais do que responder perguntas de negócio, o projeto demonstra a capacidade de projetar uma solução analítica completa, desde a compreensão das fontes de dados até a construção de uma base preparada para consumo em ferramentas de Business Intelligence.

Toda a documentação, consultas SQL e estrutura do repositório foram desenvolvidas visando reprodutibilidade, clareza técnica e alinhamento às práticas adotadas em projetos corporativos de Engenharia de Dados e Analytics.
