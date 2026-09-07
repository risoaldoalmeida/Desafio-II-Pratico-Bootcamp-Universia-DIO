<div align="center">

# 📊 Dashboard de Vendas e Performance Financeira | Power BI

### Desafio Prático • Formação Power BI Analyst • DIO

<p>

<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black">

<img src="https://img.shields.io/badge/DAX-Data%20Analysis-blue?style=for-the-badge">

<img src="https://img.shields.io/badge/Power%20Query-ETL-success?style=for-the-badge">

<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">

<img src="https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github">

<a href="https://www.dio.me/">
<img src="https://img.shields.io/badge/DIO-Formação%20Power%20BI-0E76FD?style=for-the-badge">
</a>

</p>

</div>

---

# 📖 Sobre o Projeto

Este projeto foi desenvolvido como parte do desafio prático da **Formação Power BI Analyst**, promovida pela **DIO**, utilizando como base o conjunto de dados **Financial Sample**.

O objetivo foi construir um relatório interativo para análise de **vendas, produtos, segmentos, países, unidades vendidas, descontos e custos**, aplicando recursos de visualização e navegação disponíveis no Power BI.

Além da construção dos visuais, o projeto buscou explorar recursos de **interatividade e experiência do usuário**, permitindo alternar diferentes representações dos mesmos dados por meio de botões e indicadores.

---

# 🎯 Objetivos do Desafio

O projeto foi desenvolvido com os seguintes objetivos:

- 📊 Construir um relatório analítico utilizando a base Financial Sample;
- 📈 Criar indicadores (KPIs) para acompanhamento dos principais resultados;
- 📅 Permitir a análise das vendas ao longo do tempo;
- 🌎 Analisar a distribuição das vendas por país;
- 🏢 Comparar o desempenho dos diferentes segmentos;
- 📦 Identificar os produtos com maior volume de vendas;
- 🔄 Permitir a alternância entre diferentes tipos de visualização;
- 🧭 Criar botões para melhorar a navegabilidade do relatório;
- 🎛️ Utilizar segmentadores para filtragem dos dados;
- 🎨 Aplicar princípios de organização visual e storytelling com dados.

---

# 🖥️ Dashboard

## 📊 Sales Report

A página **Sales Report** apresenta uma visão consolidada do desempenho de vendas, permitindo ao usuário analisar os resultados por período, segmento, produto e país.

O painel possui uma estrutura composta por:

- Indicadores de **Sales**;
- **Units Sold**;
- **Discounts**;
- **Média Discounts**;
- **COGS**;
- Evolução mensal das vendas;
- Análise de vendas por segmento;
- Análise de vendas por produto;
- Distribuição geográfica das vendas.

<p align="center">
<img src="images/Pag1.png" alt="Dashboard Sales Report" width="1000">
</p>

---

# 📅 Filtro por Período

O dashboard possui um segmentador de período que permite selecionar uma data inicial e uma data final.

Essa funcionalidade possibilita analisar os indicadores e gráficos considerando diferentes intervalos de tempo, tornando o relatório mais flexível para exploração dos dados.

---

# 📈 Evolução das Vendas

O gráfico **Sales x Month** apresenta a evolução das vendas ao longo dos meses.

Essa visualização permite identificar:

- Tendências de crescimento ou redução;
- Meses de maior desempenho;
- Variações sazonais;
- Pontos de maior concentração das vendas.

No período apresentado no dashboard, **outubro se destaca como o mês de maior volume de vendas**, enquanto os meses iniciais apresentam valores menores.

---

# 🏢 Sales x Segment

A análise por segmento permite compreender como as vendas estão distribuídas entre os diferentes grupos de clientes.

Foi implementada uma funcionalidade de alternância entre dois tipos de visualização:

### 📊 Bar Chart

Apresenta os valores absolutos de vendas por segmento, facilitando a comparação direta entre os grupos.

### 🥧 Pie Chart

Apresenta a participação percentual de cada segmento no total das vendas.

<p align="center">
<img src="images/Pag1.png" alt="Sales x Segment - Pie Chart" width="1000">
</p>

<p align="center">
<img src="images/Pag2.png" alt="Sales x Segment - Bar Chart" width="1000">
</p>

> 🔄 Os botões **Bar Chart** e **Pie Chart** permitem alternar entre as duas representações sem a necessidade de criar uma nova página.

---

# 📦 Sales x Product

O gráfico **Sales x Product** apresenta os produtos com maior volume de vendas.

Entre os produtos apresentados, destacam-se:

- Paseo;
- VTT;
- Velo;
- Amarilla;
- Montana;
- Carretera.

Essa visualização facilita a identificação dos produtos que possuem maior participação no faturamento.

---

# 🌎 Sales x Country

A análise geográfica permite visualizar a distribuição das vendas entre os diferentes países.

Para ampliar a experiência de exploração dos dados, foram implementadas duas formas de visualização:

### 🗺️ Map Chart

Representação geográfica dos valores de vendas por localização.

### 🌳 Treemap

Representação proporcional das vendas por país, permitindo comparar rapidamente a participação de cada mercado.

<p align="center">
<img src="images/Pag1.png" alt="Sales x Country - Map Chart" width="1000">
</p>

<p align="center">
<img src="images/Pag2.png" alt="Sales x Country - Treemap" width="1000">
</p>

> 🔄 Os botões **Treemap** e **Map Chart** permitem alternar entre as diferentes representações da análise geográfica.

---

# 🎛️ Interatividade e Navegação

Um dos principais objetivos do projeto foi aplicar recursos de interatividade para melhorar a experiência de navegação.

Foram utilizados:

- 🏠 Botões de navegação;
- 📊 Navegação entre relatórios;
- 🎛️ Segmentadores de dados;
- 🔄 Botões para alternância de visuais;
- 🗺️ Diferentes representações geográficas;
- 📊 Indicadores de desempenho;
- 📌 Organização visual dos elementos;
- 🔖 Bookmarks para controle das visualizações.

A utilização desses recursos permite que diferentes perspectivas dos mesmos dados sejam apresentadas em um espaço reduzido, evitando a necessidade de criar diversas páginas para análises semelhantes.

---

# 📊 Principais Indicadores

O painel apresenta cinco indicadores principais:

| Indicador | Descrição |
|------------|-----------|
| 💰 **Sales** | Valor total das vendas |
| 📦 **Units Sold** | Quantidade total de unidades vendidas |
| 🏷️ **Discounts** | Valor total dos descontos |
| 📉 **Média Discounts** | Média dos descontos aplicados |
| 💵 **COGS** | Custo dos produtos vendidos |

Esses indicadores fornecem uma visão inicial da performance financeira antes da exploração dos demais gráficos.

---

# 📊 Principais Visualizações

| Visualização | Objetivo |
|--------------|----------|
| 📌 Cards / KPIs | Apresentar os principais indicadores |
| 📈 Line Chart / Área | Analisar a evolução mensal das vendas |
| 📊 Bar Chart | Comparar vendas entre segmentos |
| 🥧 Pie Chart | Analisar a participação dos segmentos |
| 📊 Bar Chart de Produtos | Identificar os produtos com maior volume de vendas |
| 🗺️ Map Chart | Visualizar a distribuição geográfica das vendas |
| 🌳 Treemap | Comparar a participação das vendas por país |

---

# 🔎 Principais Insights

A análise realizada no dashboard permite identificar alguns padrões relevantes:

### 📈 Evolução temporal

As vendas apresentam variações ao longo dos meses, com destaque para o crescimento observado no segundo semestre.

O maior volume apresentado no período ocorre em **outubro**, seguido por dezembro.

### 🏢 Segmentos

O segmento **Government** apresenta a maior participação nas vendas, seguido pelo **Small Business** e **Enterprise**.

### 📦 Produtos

O produto **Paseo** apresenta o maior volume de vendas entre os produtos destacados no relatório.

### 🌎 Países

A análise geográfica demonstra concentração relevante das vendas em determinados mercados, permitindo identificar rapidamente os países com maior participação no resultado.

---

# 🛠️ Tecnologias Utilizadas

| Tecnologia | Aplicação |
|------------|-----------|
| 📊 **Microsoft Power BI Desktop** | Desenvolvimento do relatório |
| ⚙️ **Power Query** | Tratamento e transformação dos dados |
| 📈 **DAX** | Criação de medidas e indicadores |
| 📊 **Data Visualization** | Construção das visualizações |
| 🔖 **Bookmarks** | Alternância entre visualizações |
| 🎛️ **Slicers** | Filtragem dos dados |
| 🗂️ **Git** | Versionamento |
| 💻 **GitHub** | Documentação e publicação do projeto |

---

# 🧩 Recursos do Power BI Aplicados

Durante o desenvolvimento foram explorados recursos como:

- Modelagem de dados;
- Power Query;
- DAX;
- Cards;
- Gráficos de linha;
- Gráficos de barras;
- Gráfico de pizza;
- Mapas;
- Treemap;
- Segmentadores de data;
- Botões;
- Bookmarks;
- Navegação entre páginas;
- Formatação e organização de layouts;
- Interatividade entre visuais.

---

# 📁 Estrutura do Projeto

```text
📦 Desafio-Pratico-Bootcamp-Universia-DIO
│
├── 📊 Projeto.pbix
├── 📄 README.md
│
├── 📁 images
│   ├── Pag1.png
│   └── Pag2.png
│
└── 📁 dataset
    └── Financial Sample
