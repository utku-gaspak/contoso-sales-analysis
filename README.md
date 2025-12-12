# Contoso Retail Sales Analysis 📊
[![Deutsch](https://img.shields.io/badge/Lang-Deutsch-red)](README_DE.md)
## 📌 Project Overview
This project analyzes the **Contoso Retail dataset** (a simulated dataset from Microsoft) to identify revenue trends, customer purchasing behaviors, and product performance. 

The goal was to simulate a real-world business intelligence workflow: from exploring raw data to answering complex business questions regarding sales growth and customer retention.

## 🛠️ Tools & Technologies
* **SQL Dialect:** PostgreSQL
* **Techniques Used:** * **Window Functions** (`RANK`, `LEAD`, `LAG`) for moving averages and running totals.
    * **CTEs (Common Table Expressions)** to structure complex queries.
    * **Data Aggregation** (`GROUP BY`, `PIVOT`) for high-level reporting.
    * **Date Manipulation** for cohort analysis and time-series trends.

## 🔍 Key Insights & Analysis
* **Customer Retention:** Analyzed churn rates and identified that retention drops significantly after the first 3 months.
* **Revenue Trends:** Calculated rolling 3-month averages to smooth out seasonality in sales data.
* **Top Performers:** Segmented customers into high/medium/low value tiers using percentile ranking to target marketing efforts.

## 🚀 How to Run
Open the `analysis_notebook.ipynb` file to view the step-by-step logic.

