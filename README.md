# Compilado de diferentes análises exploratórias de dados (EDA) realizadas utilizando Power BI
#### Autor: Guilherme Oliveira da Rocha Cunha

Estas análises foram apresentadas no curso **Microsoft Power BI Para Business Intelligence e Data Science** oferecido pelo portal de capacitação profissional Data Science Academy (DSA) ([link](https://www.datascienceacademy.com.br/course/microsoft-power-bi-para-business-intelligence-e-data-science)). Neste curso as análises são demonstradas em laboratórios práticos ou em mini-projetos. Todos os laboratórios e mini-projetos foram refeitos do zero por mim, construídos de acordo com as instruções do professor Daniel Mendes, instrutor responsável por este curso. Todos os conjuntos de dados disponibilizados pela DSA (.csv ou .xlsx) e relatórios/dashboards feitos por mim (.pbix) estão presentes neste repositório.

## Sumário

### [1. Laboratório Prático 1 - Dashboard Analítico de Vendas Globais](#1-laboratório-prático-1---dashboard-analítico-de-vendas-globais-1)
### [2. Laboratório Prático 2 - Dashboard de Vendas, Custo, Margem de Lucro e KPI](#2-laboratório-prático-2---dashboard-de-vendas-custo-margem-de-lucro-e-kpi-1)
### [3. Mini-Projeto 1 - Análise de Campanhas de Marketing](#3-mini-projeto-1---análise-de-campanhas-de-marketing-1)
### [4. Mini-Projeto 2 - Dashboard Comercial - Performance de Vendas](#4-mini-projeto-2---dashboard-comercial---performance-de-vendas-1)

## 1. Laboratório Prático 1 - Dashboard Analítico de Vendas Globais
Neste laboratório foram utilizados dados de vendas de uma empresa fictícia que comercializa produtos em todos os cantos do mundo.

O Dashboard deve responder às seguintes perguntas de negócio:
- Pergunta 1 - Qual o valor total vendido?
- Pergunta 2 - Quantas vendas foram realizadas por categoria de produto?
- Pergunta 3 - Quantas vendas foram realizadas por país considerando a prioridade de entrega?
- Pergunta 4 - Qual foi a média de desconto nas vendas por subcategoria de produto?
- Pergunta 5 - Quais países tiveram maior média de valor de venda? Demonstre em um mapa.

O Dashboard deve dar ao usuário a possibilidade de filtrar os dados por ano, por segmento e por país.

### 1.1. Dashboard gerado
![Lab_1](https://github.com/Gui-lherme-Oliv/Data-Analysis_PowerBI/assets/123426025/cbcad32a-37dc-42c8-95a3-d433406d0ac1)

#### [Voltar ao Sumário](#sumário)
## 2. Laboratório Prático 2 - Dashboard de Vendas, Custo, Margem de Lucro e KPI
<p align="justify">Neste laboratório foram explorados os conceitos de modelagem de dados, cardinalidade, recursos de limpeza de dados do Power BI e introdução ao DAX. Foram utilizados dados de vendas fictícios obtidos em 4 diferentes tabelas: Clientes, Pedidos, Produtos e Vendas.</p>

O Dashboard deve responder às seguintes perguntas de negócio:
- Pergunta 1 - Qual foi o total de valor venda considerando cada modo de envio dos pedidos? Use um gráfico de cascata.
- Pergunta 2 - Quais mercados tiveram o maior custo médio de envio dos produtos vendidos? Use um gráfico treemap.
- Pergunta 3 - A empresa tem como objetivo (meta) manter uma média de 350 para o valor de venda todos os meses. Mostre um indicador (KPI – Key Performance Indicator) com o valor médio de venda. A empresa ficou abaixo ou acima da meta no mês de Abril/2014?
- Pergunta 4 - Considere que o lucro é equivalente a: Valor Venda - Custo Envio. Qual categoria de produto apresentou maior lucro médio?
- Pergunta 5 - Qual foi o comportamento da margem de lucro ao longo do tempo? Considere a margem de lucro como o Lucro dividido pelo Valor Venda.

### 2.1. Dashboard gerado
![Lab_2](https://github.com/Gui-lherme-Oliv/Data-Analysis_PowerBI/assets/123426025/18db1226-36dd-4de9-b5c1-98f6f367fcd4)

#### [Voltar ao Sumário](#sumário)
## 3. Mini-Projeto 1 - Análise de Campanhas de Marketing
<p align="justify">Este Mini-Projeto trouxe uma breve introdução à análise de campanhas de Marketing com o Power BI. Foram gerados 4 Dashboards, mais de 10 elementos visuais, customizações, formatações, correções nos dados e utilização de diferentes recursos do Power BI. Os dados foram previamente customizados para este Mini-Projeto e representam informações sobre clientes e campanhas de Marketing realizadas por uma empresa fictícia.</p>

Neste Mini-Projeto os relatórios foram divididos em 4 visões:
- Visão do Cliente
- Visão do Comportamento de Compra do Cliente
- Visão da Performance das Campanhas de Marketing
- Visão dos Padrões de Compra no Ponto de Venda (País)

<p align="justify">Para cada visão foram compreendidas as variáveis, criados gráficos, medidas, extraídas métricas e cruzados os dados, visando entregar aos tomadores de decisão uma visão bastante completa sobre o perfil dos clientes, os padrões de compra e a efetividade das campanhas de Marketing.</p>

### 3.1. Dashboard gerado - Visão do Cliente
![MP_1-1](https://github.com/Gui-lherme-Oliv/Data-Analysis_PowerBI/assets/123426025/11e95a31-4018-4487-9e38-6f919614c33a)

### 3.2. Dashboard gerado - Visão do Comportamento de Compra do Cliente
![MP_1-2](https://github.com/Gui-lherme-Oliv/Data-Analysis_PowerBI/assets/123426025/6964d293-9cbb-4e95-8f87-e6ff850d442e)

### 3.3. Dashboard gerado - Visão da Performance das Campanhas de Marketing
![MP_1-3](https://github.com/Gui-lherme-Oliv/Data-Analysis_PowerBI/assets/123426025/0814f65a-59f0-4a38-9166-c4447ce469bf)

### 3.4. Dashboard gerado - Visão dos Padrões de Compra no Ponto de Venda (País)
![MP_1-4](https://github.com/Gui-lherme-Oliv/Data-Analysis_PowerBI/assets/123426025/50cbaff8-1cdb-464c-8b47-1d5dbe5a4686)

#### [Voltar ao Sumário](#sumário)

## 4. Mini-Projeto 2 - Dashboard Comercial - Performance de Vendas
<p align="justify">Neste Mini-Projeto foi trabalhado um problema da área comercial, especificamente para analisar a performance de vendas de uma empresa fictícia. Ele trouxe uma breve introdução à análise de dados comerciais com o Power BI. Foram construídas diversas visualizações para compreender a performance de vendas de uma empresa fictícia por diferentes ângulos. Neste Mini-Projeto aprendi a trabalhar com interessantes recursos do Power BI como a Narrativa Inteligente, Principais Influenciadores, Gráfico de Faixas e criação de menu para índice do Dashboard.</p>

#### [Voltar ao Sumário](#sumário)
