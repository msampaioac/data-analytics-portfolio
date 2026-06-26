# 📊 Storytelling Analítico do Dashboard

# Painel Estratégico da Educação Brasileira (2019--2023)

## Objetivo Geral

Este documento descreve a proposta funcional do dashboard desenvolvido
em Power BI a partir da base analítica construída em SQL no Google
BigQuery. O objetivo é orientar o desenvolvimento do painel, definindo
quais perguntas de negócio cada página responderá, quais KPIs serão
apresentados, quais visualizações serão utilizadas e quais decisões
poderão ser apoiadas.

------------------------------------------------------------------------

# Página 1 --- Visão Executiva

## Objetivo

Fornecer um panorama nacional da educação brasileira.

## Pergunta principal

**O que está acontecendo com a educação brasileira entre 2019 e 2023?**

## Perguntas respondidas

-   Quantos estudantes existem?
-   Como evoluíram as matrículas?
-   Como está distribuído o ensino?
-   Como está dividida a rede pública e privada?
-   Onde estão concentrados os estudantes?
-   Como está a infraestrutura?
-   Qual o percentual de estudantes com deficiência?

## KPIs

-   Total de Estudantes
-   Ensino Fundamental
-   Ensino Médio
-   Ensino Superior
-   Crescimento do Período
-   Rede Pública
-   Rede Privada
-   Estudantes com Deficiência

## Gráficos

-   Linha: Evolução das Matrículas
-   Colunas: Distribuição por Nível de Ensino
-   Rosca: Rede Pública × Privada
-   Mapa: Estudantes por Estado
-   Barras: Ranking dos Estados
-   Cartões: Infraestrutura (Internet, Biblioteca, Laboratórios e
    Quadra)

## Decisões apoiadas

-   Identificar tendências nacionais.
-   Detectar regiões prioritárias.
-   Direcionar análises detalhadas.

------------------------------------------------------------------------

# Página 2 --- Perfil Demográfico

## Objetivo

Conhecer quem são os estudantes brasileiros.

## Pergunta principal

**Quem são os estudantes brasileiros?**

## Perguntas respondidas

-   Como está distribuído o sexo?
-   Qual a faixa etária predominante?
-   Como está distribuída a raça/cor?
-   Qual a nacionalidade predominante?
-   Como essas características variam por nível de ensino?

## KPIs

-   Homens
-   Mulheres
-   Idade Média
-   Estudantes com Deficiência
-   Nacionalidades

## Gráficos

-   Barras: Sexo
-   Pirâmide Etária
-   Donut: Raça/Cor
-   Colunas: Faixa Etária
-   Mapa: Perfil por Estado

## Decisões apoiadas

-   Identificar perfis predominantes.
-   Apoiar políticas de inclusão.
-   Comparar perfis regionais.

------------------------------------------------------------------------

# Página 3 --- Distribuição Geográfica

## Objetivo

Analisar onde estão concentradas as matrículas.

## Pergunta principal

**Onde estão os estudantes brasileiros?**

## Perguntas respondidas

-   Quais regiões possuem mais estudantes?
-   Quais estados concentram mais matrículas?
-   Quais municípios possuem maior participação?

## KPIs

-   Total por Região
-   Total por Estado
-   Total por Município

## Gráficos

-   Mapa do Brasil
-   Ranking dos Estados
-   Ranking dos Municípios
-   Linha: Evolução Regional

## Decisões apoiadas

-   Planejamento regional.
-   Distribuição de recursos.
-   Comparações geográficas.

------------------------------------------------------------------------

# Página 4 --- Infraestrutura Escolar

## Objetivo

Avaliar as condições estruturais das escolas.

## Pergunta principal

**Como está a infraestrutura escolar brasileira?**

## Perguntas respondidas

-   Qual o acesso à internet?
-   Quantas escolas possuem biblioteca?
-   Existem laboratórios?
-   Há quadras esportivas?
-   Como esses indicadores variam entre estados?

## KPIs

-   Internet
-   Biblioteca
-   Sala de Leitura
-   Laboratório de Informática
-   Laboratório de Ciências
-   Quadra
-   Água Potável
-   Energia Elétrica

## Gráficos

-   Barras Horizontais
-   Radar
-   Heatmap
-   Mapa Temático

## Decisões apoiadas

-   Priorizar investimentos.
-   Identificar desigualdades regionais.

------------------------------------------------------------------------

# Página 5 --- Inclusão e Acessibilidade

## Objetivo

Analisar indicadores de inclusão.

## Pergunta principal

**Como está a inclusão dos estudantes brasileiros?**

## Perguntas respondidas

-   Quantos estudantes possuem deficiência?
-   Como evoluiu esse indicador?
-   Como está o transporte escolar?

## KPIs

-   Estudantes com Deficiência
-   Transporte Escolar
-   Percentual de Inclusão

## Gráficos

-   Linha Temporal
-   Barras
-   Mapa
-   Indicadores Percentuais

## Decisões apoiadas

-   Planejamento de ações inclusivas.
-   Avaliação de políticas públicas.

------------------------------------------------------------------------

# Página 6 --- Ensino Superior

## Objetivo

Analisar os indicadores do Ensino Superior.

## Pergunta principal

**Como está estruturado o Ensino Superior brasileiro?**

## Perguntas respondidas

-   Qual área do conhecimento possui mais matrículas?
-   Como está dividido o ensino presencial e EAD?
-   Como está o financiamento estudantil?
-   Como está a reserva de vagas?

## KPIs

-   Matrículas
-   Financiamento
-   Reserva de Vagas
-   Apoio Social
-   Mobilidade Acadêmica

## Gráficos

-   Treemap
-   Sunburst
-   Barras
-   Donut
-   Linha

## Decisões apoiadas

-   Avaliar expansão do ensino superior.
-   Apoiar planejamento acadêmico.

------------------------------------------------------------------------

# Página 7 --- Comparativos

## Objetivo

Comparar indicadores entre regiões, estados e anos.

## Pergunta principal

**Como diferentes recortes se comportam entre si?**

## Perguntas respondidas

-   Estado × Estado
-   Região × Região
-   Ano × Ano
-   Rede Pública × Privada
-   Ensino Fundamental × Médio × Superior

## KPIs

-   Diferença Absoluta
-   Diferença Percentual
-   Crescimento

## Gráficos

-   Barras Agrupadas
-   Linha Comparativa
-   Tabela Dinâmica
-   Dispersão

## Decisões apoiadas

-   Benchmarking.
-   Comparações estratégicas.

------------------------------------------------------------------------

# Página 8 --- Insights Estratégicos

## Objetivo

Destacar automaticamente os principais achados da análise.

## Pergunta principal

**Quais informações exigem atenção imediata?**

## Perguntas respondidas

-   Qual estado mais cresceu?
-   Onde há maior deficiência de infraestrutura?
-   Qual região apresenta melhores indicadores?
-   Quais tendências foram observadas?

## KPIs

-   Top 5 Crescimentos
-   Top 5 Reduções
-   Melhor Infraestrutura
-   Maior Inclusão

## Gráficos

-   Rankings
-   Cartões Inteligentes
-   Heatmap
-   Linha de Tendência

## Decisões apoiadas

-   Definição de prioridades.
-   Formulação de políticas públicas.
-   Comunicação executiva.

------------------------------------------------------------------------

# Navegação

Fluxo recomendado:

1.  Visão Executiva
2.  Perfil Demográfico
3.  Distribuição Geográfica
4.  Infraestrutura Escolar
5.  Inclusão e Acessibilidade
6.  Ensino Superior
7.  Comparativos
8.  Insights Estratégicos
