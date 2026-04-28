# Geographic Concentration of Transactions

Exploratory data analysis focused on geographic concentration of transactions
and the associated business and operational risk.

## Overview
This project analyzes the geographic distribution of payment transactions
to identify concentration risk and dependency on specific countries or regions.

The objective is to provide business-oriented insights into how transaction
activity is distributed geographically and to highlight potential strategic,
operational, and market risks derived from high geographic concentration.

## Business Questions

- Which countries generate the majority of payment transactions?
- Is transaction activity overly concentrated in a small number of markets?
- What are the potential risks associated with this level of concentration?
- How does transaction concentration evolve over time for the most relevant countries


## Data Source
The data used in this analysis comes from the **European Central Bank (ECB) –
Payments Transactions statistics (PAY dataset)**.

The dataset was downloaded directly from the ECB Data Portal and stored locally
as a CSV file to ensure stability, transparency, and full reproducibility
of the analysis.



## Dataset Handling
Raw data is stored without modification in the `data/raw/` directory.
All cleaning, aggregation, and transformations are performed within the
analysis workflow to preserve data lineage and reproducibility.

## Approach
1. Data loading and validation
2. Data cleaning and standardization
3. Aggregation of transactions by country
4. Calculation of country-level transaction shares
5. Analysis of cumulative concentration (Pareto-style analysis)
6. Visualization of geographic concentration patterns
7. Trend analysis of transaction volumes over time for the top contributing countries

## Key Insights
- Transaction activity is highly concentrated in a limited number of countries.
- A small group of markets accounts for a disproportionate share of total transactions.
- The distribution exhibits a strong concentration pattern, increasing exposure
  to country-specific economic and regulatory risks.

- Trend analysis shows how transaction volumes for top countries evolve over time,
  helping identify structural changes, growth patterns, and emerging concentration risks


## Tools Used
- Python (pandas, numpy)
- Matplotlib / Seaborn
- Jupyter Notebook


## Next Steps
- Extend temporal analysis to include year-over-year growth rates
- Compare geographic concentration across different payment instruments
- Assess potential diversification scenarios and their impact on risk exposure


 ## How to Run

1. Clone the repository
```bash
   git clone https://github.com/TU_USUARIO/geographic-trx-concentration.git
   cd geographic-trx-concentration
```

2. Install dependencies
```bash
   pip install -r requirements.txt
```

3. Launch Jupyter and open the notebook
```bash
   jupyter notebook notebooks/01_geographic_concentration_analysis.ipynb
