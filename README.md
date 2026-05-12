# Customer Churn Cohort Analysis

## Project Overview
A telecom company is losing 26.5% of its customers and does not know why.
This project uses advanced SQL - window functions, CTEs and multi-dimensional 
segmentation — to identify exactly who churns, when and what drives it.

## Business Questions Answered
1. What is the overall churn rate and how many customers are at risk?
2. Which customer segments have the highest churn concentration?
3. Does contract type predict churn more than any other variable?
4. How does tenure affect churn — do customers leave early or after years?
5. What is the revenue impact of churn by segment?

## Tools Used
- **MySQL** — all analysis done in SQL (CTEs, window functions, aggregations)
- **MySQL Workbench** — query execution and result screenshots
- **Dataset** — IBM Telco Customer Churn (Kaggle, 7,043 customers)

## Key Findings

1. **26.54% overall churn rate** — 1,869 customers lost, $139K monthly revenue at risk ($1.67M annualized)
2. **Contract type is the strongest predictor** — Month-to-month: 42.71% churn vs Two-year: 2.83% (15x difference)
3. **New customers are in crisis** — 47.44% of customers in their first 12 months churn. Drops to 6.61% after 5 years
4. **Fiber optic without security = 49.36% churn** — adding online security cuts it to 21.81%
5. **Electronic check + paperless billing = 49.77% churn** — 5x higher than credit card users
6. **High-value customers are the ones leaving** — top churned customers pay $111–$118/month on Fiber optic

## Project Structure
customer-churn-analysis/
│
├── sql/          # All SQL queries with annotations
├── visuals/      # Query result screenshots
└── data/         # Dataset source reference

## Status
✅ Complete — SQL Diagnostic Analysis (6 queries) + Python Visualizations (4 charts)

## Author
[Cynthia Wanjiku Ng'ang'a] | Business Analytics Graduate Student  
[https://www.linkedin.com/in/cynthia-ng%E2%80%99ang%E2%80%99a-b3b764350/]
