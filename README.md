# -market-basket-analysis-
Market basket analysis on 522,000+ retail transactions using the Apriori algorithm to identify 216 association rules and build a product recommendation engine.

# Market Basket Analysis & Product Recommendation Engine

## Overview
This project applies Market Basket Analysis to a large retail dataset of 
over 522,000 transactions to uncover hidden purchasing patterns and build 
a product recommendation engine. Using the Apriori algorithm, 216 
association rules were identified to support cross-selling and targeted 
marketing strategies.

## Dataset
- Source: UCI Online Retail Dataset (retail.csv)
- 522,000+ transactions
- Features: BillNo, ItemName, Quantity, Date, Price, CustomerID, Country

## Tools & Libraries
- Python, Pandas, Mlxtend, Apriori Algorithm

## Project Workflow
- Data loading and exploratory analysis
- Missing value treatment
- Data transformation into basket format
- Apriori algorithm implementation (minimum lift: 1.1)
- Association rules generation and filtering
- Product recommendation engine development

## Key Findings
- 216 association rules identified across all transactions
- Customers buying "PACK OF 72 RETROSPOT CAKE CASES" are likely to 
  purchase "60 TEATIME FAIRY CAKE CASES"
- Customers buying "Regency Cakestand 3 Tier" are likely to also 
  purchase "Roses Regency Teacup and Saucer"
- United Kingdom leads in transaction volume with distinct purchasing 
  patterns compared to other countries
- Country-level analysis reveals opportunities for region-specific 
  marketing campaigns

## Business Applications
- Cross-selling and upselling opportunities
- Targeted marketing campaigns for high-value customers
- Product placement and recommendation optimisation
- Regional purchasing behaviour analysis

## Conclusion
Market Basket Analysis provides actionable insights for businesses 
looking to optimise marketing strategies, improve customer satisfaction, 
and drive revenue growth through data-driven product recommendations.
