**PT-BR Portuguese**
Relatório de Análise para Investimento e Expansão
Este documento apresenta o passo a passo da análise de dados de Cadeia de Suprimentos (Supply Chain) para subsidiar a decisão estratégica de qual planta/cidade deve receber os recursos de expansão e investimentos.

🛠️ Passo a Passo da Análise no Código
Preparação dos Dados de Lucro Líquido:
Criamos uma nova métrica financeira (Profit) calculando a diferença direta entre a receita gerada (Revenue generated) e os custos totais associados (Costs).
Agrupamento Estratégico (groupby por Location):
Consolidamos as informações essenciais de cada planta: Lucro Total, Receita Total, Volume Total de Produtos Vendidos, Nível Médio de Estoque e o Custo Médio de Manufatura por item.
Criação do Índice de Giro de Estoque:
Criamos a métrica Stock_Turnover_Index que divide o Volume de Vendas pelo Nível de Estoque Médio. Isso mede a eficiência logística: quanto maior o índice, mais rápido o estoque gira, evitando capital de giro paralisado.
Visualização de Resultados (KPIs):
Plotamos 4 gráficos comparativos para avaliar o desempenho financeiro, volume de mercado, eficiência de estoque e custos de fabricação de cada planta.
🏆 A Planta Vencedora: Mumbai 🌟
Com base na análise quantitativa de todos os KPIs, a planta de Mumbai é a mais recomendada para receber os investimentos de expansão.

📊 Justificativa Baseada nos Dados:
Líder em Rentabilidade (Lucro Líquido):
Mumbai gerou o maior Lucro Líquido total entre todas as praças, acumulando R 128.331,50∗∗.ElasuperaKolkata(R  124.795,81) e fica muito à frente de Delhi (R 72.804,13).2.∗∗MelhorControleeGirodeEstoque(EficiênciaLogística):∗∗∗Mumbaipossuiomaior∗∗ÍndicedeGirodeEstoque(222.50)∗∗.IssoprovaqueaplantadeMumbaiéextremamenteágileeficienteemvenderoquearmazena,minimizandodesperdíciosecustosdeestocagemdeprodutosparados.3.∗∗CustoOperacionalAltamenteCompetitivo:∗∗∗Mumbaipossuio∗∗menorcustomédiodemanufaturaporitem(R  36,73) comparado a todas as outras plantas. Isso significa que expandir a produção em Mumbai é financeiramente mais barato e gera margens de lucro unitárias melhores.
Excelente Penetração de Mercado:
É a segunda maior planta em volume absoluto de vendas (9.426 unidades), demonstrando que já possui canais de escoamento e demanda consolidados para absorver um aumento de capacidade produtiva.
📈 Resumo do Ranking de Decisão:
1º Lugar (Recomendado): Mumbai (Maior Lucro, Maior Giro de Estoque, Menor Custo de Fabricação).
2º Lugar (Alternativa): Kolkata (Excelente volume de vendas e lucro, mas custo de fabricação ligeiramente superior ao de Mumbai).
3º Lugar: Chennai (Desempenho intermediário estável).
4º Lugar: Bangalore (Giro de estoque muito baixo e custos de fabricação elevados).
5º Lugar: Delhi (Menor lucro líquido gerado e baixa eficiência relativa de estoque).

**EN English**

# Investment and Expansion Analysis Report
This document presents the step-by-step process of Supply Chain data analysis to support the strategic decision of which plant/city should receive expansion resources and investments.

## 🛠️ Step-by-Step Analysis in the Code
**Net Profit Data Preparation:**
We created a new financial metric (`Profit`) by calculating the direct difference between the revenue generated (`Revenue generated`) and the associated total costs (`Costs`).

**Strategic Grouping (`groupby` by Location):**
We consolidated the key information for each plant: Total Profit, Total Revenue, Total Volume of Products Sold, Average Inventory Level, and Average Manufacturing Cost per Item.

**Stock Turnover Index Creation:**
We created the `Stock_Turnover_Index` metric by dividing Sales Volume by Average Inventory Level. This measures logistics efficiency: the higher the index, the faster inventory moves, preventing working capital from being tied up in stock.

**Results Visualization (KPIs):**
We plotted four comparative charts to evaluate the financial performance, market volume, inventory efficiency, and manufacturing costs of each plant.

## 🏆 The Winning Plant: Mumbai 🌟
Based on the quantitative analysis of all KPIs, the Mumbai plant is the most recommended location to receive expansion investments.

## 📊 Data-Driven Justification:

**1. Highest Profitability (Net Profit):**
Mumbai generated the highest total net profit among all locations, reaching **R$ 128,331.50**. It outperformed Kolkata (R$ 124,795.81) and significantly exceeded Delhi (R$ 72,804.13).

**2. Best Inventory Management and Turnover (Logistics Efficiency):**
Mumbai has the highest **Stock Turnover Index (222.50)**. This demonstrates that the Mumbai plant is extremely efficient at selling its stored inventory, minimizing waste and storage costs associated with slow-moving products.

**3. Highly Competitive Operating Costs:**
Mumbai has the **lowest average manufacturing cost per item (R$ 36.73)** compared to all other plants. This means that expanding production in Mumbai is financially more cost-effective and generates better unit profit margins.

**4. Excellent Market Penetration:**
It ranks second in total sales volume (9,426 units), demonstrating that it already has established distribution channels and market demand to support an increase in production capacity.

## 📈 Decision Ranking Summary:

**1st Place (Recommended):** Mumbai (Highest Profit, Highest Stock Turnover, Lowest Manufacturing Cost).
**2nd Place (Alternative):** Kolkata (Excellent sales volume and profit, but slightly higher manufacturing costs than Mumbai).
**3rd Place:** Chennai (Stable, intermediate performance).
**4th Place:** Bangalore (Very low stock turnover and high manufacturing costs).
**5th Place:** Delhi (Lowest net profit and relatively low inventory efficiency).

# Libraries-Python---Data-Science-Studies-

A collection of Python projects and data science studies developed throughout my Data Science specialization at UFOP.

## About

This repository gathers the notebooks and exercises I produced while studying data analysis and data science with Python. Each notebook is self-contained and can be run on Google Colab.

## Contents

| Notebook | Topic | Main libraries |
|---|---|---|
| [Aula_04_lista_exercicios_spotify_pandas](./Aula_04_lista_exercicios_spotify_pandas.ipynb) | Pandas exercises using a Spotify dataset | pandas |
| _More notebooks coming soon_ | | |

## Tech stack

- Python
- pandas
- Google Colab / Jupyter Notebook

## How to run

Open any notebook in Google Colab using the "Open in Colab" badge at the top of the file, or download the `.ipynb` and open it in Jupyter.

## Author

**Gleisson Leonardo Pereira**
Data Analyst | Power BI • SQL • Python | Supply Chain & Operations background

[LinkedIn](https://www.linkedin.com/in/SEU-PERFIL) · [GitHub](https://github.com/gleisspe)
