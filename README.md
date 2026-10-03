# Churn Analysis and Customer Intelligence

Churn analysis of an OTT subscription platform using Python and SQL.

## What I did
- Pulled 3 tables (customers, subscriptions, support) from SQLite with sqlite3 and pandas
- Cleaned the data and built features: churn flag, tenure, risk tier
- Calculated KPIs: churn rate, churn by plan and state, ARPU, revenue lost, escalation rate
- Visualised results with matplotlib and seaborn

## Key findings
- Churn rate 28.6% (6 of 21 customers)
- Basic plan churns at 60% vs 14.3% for Premium
- Monthly revenue lost to churn: 73.94 (18.7% of total)

## Files
- `notebook/` full analysis code
- `report/` PDF and HTML report

## Tools
Python, pandas, numpy, sqlite3, matplotlib, seaborn

## Data
Practice dataset (customer_churn database). Add the source or course name here if it came from one.

Author: Sohail Khan
