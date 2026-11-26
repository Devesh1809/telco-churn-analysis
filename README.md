# Telco Customer Churn Analysis

## Business Problem
Konte customers company soduun jatat ani ka? Retention strategy sathi data-driven insights shodhne.

## Dataset
IBM Telco Customer Churn (Kaggle): 7,043 customers, 50 columns.

## Tools
Python (pandas, matplotlib, seaborn), Google Colab, Power BI

## Steps
1. Data understanding ani cleaning (nulls, data types, duplicates)
2. EDA: churn by contract, tenure, internet type, payment method
3. Power BI dashboard: KPIs, charts, slicers

## Dashboard


![Dashboard](Screenshot%202026-11-26%20152359.png)



## Key Insights
- Overall churn rate **26.5%** (1,869 of 7,043 customers)
- **Month-to-month** contract churn 46% vs Two Year 3%
- **0-12 months** tenure churn 47%, 49-72 months fakt 10%
- **Fiber Optic** churn 41% vs DSL 19%
- Top churn reasons: competitor offers

## Recommendations
1. Month-to-month customers la yearly plan var discount dya
2. Pahilya 6 mahinyat onboarding offer ani follow-up call
3. Fiber Optic pricing ani service quality tapasa
4. Competitor offers match honare retention offers tayar kara

## Files
- `Untitled42.ipynb`: Python cleaning + EDA
- `telco customers dashboard.powerBi.pbix`: Power BI dashboard
- `powerbi_churn.csv`: cleaned dataset
