# Dicionário de Dados

## Projeto

**Perfil dos Estudantes Brasileiros (2019–2023)**

**Fonte dos Dados**

- Base dos Dados
- INEP – Censo Escolar
- INEP – Censo da Educação Superior
- Diretório de Municípios (IBGE)

---

## Objetivo

Este dicionário descreve todos os campos produzidos pela consulta SQL desenvolvida para integrar dados do Censo Escolar e do Censo da Educação Superior em uma única base analítica destinada a projetos de Business Intelligence, Analytics e Ciência de Dados.

---

# Dicionário de Campos

| Campo | Tipo | Descrição |
|---------|------|-----------|
| ano | Inteiro | Ano de referência dos dados (2019–2023). |
| fonte | Texto | Base de origem dos dados (`CENSO_ESCOLAR` ou `CENSO_SUPERIOR`). |
| nivel_ensino | Texto | Nível de ensino analisado (Ensino Fundamental, Ensino Médio ou Ensino Superior). |
| sigla_uf | Texto | Sigla da Unidade da Federação. |
| id_municipio | Inteiro | Código IBGE do município. |
| nome_municipio | Texto | Nome do município. |
| regiao | Texto | Região geográfica do Brasil (Norte, Nordeste, Centro-Oeste, Sudeste ou Sul). |
| sexo | Texto | Sexo do estudante. Para o Ensino Superior, apresentado de forma agregada. |
| raca_cor | Texto | Raça/cor declarada pelo estudante. |
| faixa_etaria | Texto | Faixa etária construída a partir da idade do estudante. |
| nacionalidade | Texto | Nacionalidade declarada pelo estudante. |
| rede | Texto | Rede de ensino (Pública ou Privada). |
| tipo_localizacao | Texto | Localização da escola (Urbana ou Rural). |
| tipo_localizacao_diferenciada | Texto | Indica escolas localizadas em áreas indígenas, quilombolas, assentamentos ou outras localidades diferenciadas. |
| tipo_modalidade_ensino | Texto | Modalidade do curso superior (Presencial ou Educação a Distância). |
| tipo_grau_academico | Texto | Grau acadêmico do curso (Bacharelado, Licenciatura ou Tecnológico). |
| tipo_organizacao_academica | Texto | Organização acadêmica da Instituição de Ensino Superior. |
| tipo_organizacao_administrativa | Texto | Categoria administrativa da Instituição de Ensino Superior. |
| area_conhecimento | Texto | Área geral do conhecimento do curso superior. |

---

# Indicadores Quantitativos

| Campo | Descrição |
|---------|-----------|
| qtd_estudantes | Quantidade total de estudantes ou matrículas no agrupamento. |
| qtd_com_deficiencia | Quantidade de estudantes com deficiência. |
| qtd_usa_transporte_publico | Quantidade de estudantes que utilizam transporte escolar público. |
| qtd_em_escola_com_agua_potavel | Estudantes matriculados em escolas com água potável. |
| qtd_em_escola_com_energia_rede_publica | Estudantes matriculados em escolas com energia da rede pública. |
| qtd_em_escola_com_esgoto_rede_publica | Estudantes matriculados em escolas com rede pública de esgoto. |
| qtd_em_escola_com_internet | Estudantes matriculados em escolas com acesso à internet. |
| qtd_em_escola_com_internet_alunos | Estudantes matriculados em escolas com internet disponível para alunos. |
| qtd_em_escola_com_biblioteca | Estudantes matriculados em escolas com biblioteca. |
| qtd_em_escola_com_biblioteca_sala_leitura | Estudantes matriculados em escolas com biblioteca ou sala de leitura. |
| qtd_em_escola_com_lab_informatica | Estudantes matriculados em escolas com laboratório de informática. |
| qtd_em_escola_com_lab_ciencias | Estudantes matriculados em escolas com laboratório de ciências. |
| qtd_em_escola_com_quadra | Estudantes matriculados em escolas com quadra esportiva. |
| qtd_financiamento | Matrículas do Ensino Superior com financiamento estudantil. |
| qtd_reserva_vaga | Matrículas realizadas por reserva de vagas (cotas). |
| qtd_apoio_social | Matrículas de estudantes beneficiados por programas de apoio social. |
| qtd_atividade_extracurricular | Matrículas de estudantes participantes de atividades extracurriculares. |
| qtd_mobilidade_academica | Matrículas de estudantes participantes de programas de mobilidade acadêmica. |

---

# Indicadores Percentuais

| Campo | Descrição |
|---------|-----------|
| perc_com_deficiencia | Percentual de estudantes com deficiência em relação ao total de estudantes. |
| perc_usa_transporte_publico | Percentual de estudantes que utilizam transporte escolar público. |
| perc_em_escola_com_internet | Percentual de estudantes matriculados em escolas com acesso à internet. |
| perc_em_escola_com_biblioteca | Percentual de estudantes matriculados em escolas com biblioteca. |
| perc_em_escola_com_lab_informatica | Percentual de estudantes matriculados em escolas com laboratório de informática. |
| perc_em_escola_com_quadra | Percentual de estudantes matriculados em escolas com quadra esportiva. |
| perc_financiamento | Percentual de matrículas do Ensino Superior com financiamento estudantil. |
| perc_reserva_vaga | Percentual de matrículas realizadas por reserva de vagas. |
| perc_apoio_social | Percentual de matrículas beneficiadas por programas de apoio social. |
| perc_atividade_extracurricular | Percentual de matrículas com participação em atividades extracurriculares. |
| perc_mobilidade_academica | Percentual de matrículas com participação em programas de mobilidade acadêmica. |

---

# Aplicação da Base

A base analítica produzida por esta consulta foi desenvolvida para apoiar análises sobre o perfil dos estudantes brasileiros e pode ser utilizada em:

- Business Intelligence (Power BI, Tableau, Looker Studio e Qlik Sense);
- Análise Exploratória de Dados (EDA);
- Estudos acadêmicos;
- Projetos de Ciência de Dados;
- Planejamento e monitoramento de políticas públicas;
- Produção de indicadores educacionais;
- Dashboards gerenciais;
- Análises estatísticas e temporais.

---

# Observações

- O período analisado compreende os anos de **2019 a 2023**.
- Os dados são provenientes exclusivamente de bases públicas oficiais disponibilizadas pela **Base dos Dados**.
- A consulta integra múltiplas tabelas utilizando **CTEs**, **JOINs**, **agregações** e **indicadores percentuais**.
- O desenvolvimento contou com apoio de **Inteligência Artificial** para revisão da lógica, identificação de inconsistências, melhoria da estrutura SQL e documentação técnica, com validação final realizada no Google BigQuery.

---

## Autor

**Marcelo Sampaio**

Projeto desenvolvido para fins de estudo em SQL Analítico, Engenharia de Dados e Business Intelligence utilizando dados públicos brasileiros.
