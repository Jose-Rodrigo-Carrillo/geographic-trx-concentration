# geographic-trx-concentration
Exploratory data analysis focused on geographic concentration of transactions and business risk.


# Geographic Concentration of Transactions

## Overview
This project analyzes the geographic distribution of transactions to identify concentration risk
and dependency on specific countries or regions.

The goal is to provide business insights into how transaction volume is distributed geographically
and highlight potential operational or strategic risks.

## Business Questions
- Which countries generate the majority of transactions?
- Is the business overly dependent on a small number of markets?
- How strong is the long tail of low-volume countries?

## Dataset
The analysis is based on a synthetic but realistic transactions dataset containing:
- Country
- Transaction count
- Transaction volume
- Channel (POS / e-commerce)
- Date

## Approach
1. Data cleaning and validation
2. Aggregation by country
3. Percentage contribution analysis
4. Visualization of concentration patterns

## Key Insights
- A small number of countries account for a large share of total transactions.
- The distribution follows a strong Pareto pattern.
- Geographic concentration represents both efficiency and risk.

## Tools Used
- Python (pandas, numpy)
- Matplotlib / Seaborn

## Next Steps
- Analyze trends over time
- Compare concentration across payment channels
- Assess diversification scenarios
