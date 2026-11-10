# Churn_Analysis_and_Customer-Intelligence-Python

# OTT Customer Churn Analysis & Customer Intelligence

## Project Overview
This project focuses on analyzing customer churn for an OTT subscription platform to understand customer behavior, identify churn patterns, and evaluate their impact on revenue.

Using SQL and Python, customer information, subscription details, and customer support data were analyzed to identify churn trends, understand customer retention, and generate actionable business insights.

## Business Problem
Customer churn directly impacts subscription revenue and long-term customer value. The objective of this project is to:

- Identify customers who have churned and understand their behavior.
- Analyze churn across subscription plans, contract types, and geographical locations.
- Understand the relationship between customer support escalations and churn.
- Identify high-risk customer segments.
- Recommend strategies to improve customer retention and reduce revenue loss.

## Tech Stack
- **SQL:** Data extraction and relational data analysis
- **Python:** Data analysis and feature engineering
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **SQLite3:** Database connectivity and SQL-Python integration

## Dataset Structure
The project uses three relational tables:

| Table | Description |
|---|---|
| `db_customer` | Customer demographics and geographical information |
| `db_subscription` | Subscription plans, contracts, charges, churn scores, and cancellation details |
| `db_support` | Customer complaints, escalations, CSAT scores, and support comments |

## Project Workflow
1. **SQL Database Integration:** Connected the SQL database with Python using SQLite3 and Pandas.
2. **Data Extraction:** Retrieved customer, subscription, and support information using SQL queries.
3. **Data Cleaning:** Handled data types, missing values, column selection, and data quality checks.
4. **Feature Engineering:** Created calculated metrics and transformed data for analysis.
5. **Exploratory Data Analysis:** Analyzed churn patterns using aggregations, grouping, and pivot tables.
6. **Data Visualization:** Created visualizations using Matplotlib and Seaborn.
7. **Business Insights:** Identified churn patterns and developed data-driven retention recommendations.

## Key Findings

- **Overall Churn Rate:** 28.6%
- **Retention Rate:** 71.4%
- **Monthly Contract Churn:** 55.6%
- **Annual Contract Churn:** 8.3%
- **Average Customer Tenure:** 1,451 days
- **ARPU:** ₹18.8
- **Revenue Loss Due to Churn:** 74
- **CLTV Lost:** 2,047
- **Revenue Loss Percentage:** 18%

### Important Observations
- Monthly contract customers showed significantly higher churn than annual contract customers.
- The Basic subscription plan contributed the highest number of churned customers.
- Karnataka was the most affected state.
- September 2024 recorded the highest churn.
- Monthly subscriptions showed considerably higher churn compared to annual subscriptions.

## Business Recommendations

- Investigate churn patterns in Karnataka to identify possible pricing, technical, or customer support issues.
- Review pricing and subscription changes affecting Basic plan customers.
- Investigate competitor switching and customer dissatisfaction.
- Prioritize customers with medium and high churn risk scores.
- Identify high-value customers using Customer Lifetime Value (CLTV).
- Improve customer retention through targeted communication and support interventions.
- Encourage suitable customers to migrate from monthly to annual subscription plans.

## KPIs Analyzed
- Churn Rate
- Retention Rate
- Churn by Plan Type
- Churn by State
- Average Revenue Per User (ARPU)
- Average Customer Tenure
- Revenue at Risk
- Escalation Rate
- Average Complaints per Customer
- Customer Support Escalations vs. Churn

## Project Objective
The project demonstrates how SQL and Python can be used together to transform customer data into meaningful business insights, helping businesses understand churn, improve retention, and minimize revenue loss.

---
**Tools:** SQL | Python | Pandas | NumPy | Matplotlib | Seaborn | SQLite3

**Domain:** Customer Analytics | Subscription Analytics | Business Analytics | Revenue Analytics
