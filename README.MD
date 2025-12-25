Retail Sales & Customer Analytics — End-to-End Project
Overview

This project is a complete end-to-end retail analytics solution demonstrating real-world data analysis, customer analytics, predictive modeling, SQL analysis, and executive dashboarding.

The work simulates how data analysts support business decision-making by transforming raw transactional data into actionable insights and strategic recommendations.

Business Questions Addressed

How is overall sales and profitability performing?

Which regions and product categories drive the most revenue?

Who are the most valuable customers?

How strong is customer retention?

Can we predict which customers are likely to make repeat purchases?

Project Structure

Retail_Project_Fresh/
├── dashboards/
│   ├── executive_dashboard.png
│   └── customer_intelligence_dashboard.png
│
├── data/
│   ├── raw/
│   │   └── retail_sales_data.csv
│   └── processed/
│       ├── cleaned_retail_sales.csv
│       ├── customer_clv.csv
│       ├── customer_segments.csv
│       ├── monthly_kpis.csv
│       └── rfm_analysis.csv
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_cleaning_preprocessing.ipynb
│   ├── 03_exploratory_data_analysis.ipynb
│   ├── 04_customer_segmentation.ipynb
│   ├── 05_kpi_dashboard_preparation.ipynb
│   ├── 06_sqlite_sql_analysis.ipynb
│   └── 07_predictive_modelling.ipynb
│
├── outputs/
│   ├── figures/
│   │   ├── 01_missing_values.png
│   │   ├── 03_outliers_before_treatment.png
│   │   ├── 04_outliers_after_treatment.png
│   │   ├── 05_numerical_distributions.png
│   │   ├── 06_categorical_distributions.png
│   │   ├── 09_correlation_matrix.png
│   │   └── 10_monthly_sales_trend.html
│   └── reports/
│       ├── 01_initial_inspection_report.txt
│       ├── 02_cleaning_report.txt
│       ├── 03_eda_key_findings.txt
│       ├── executive_summary.txt
│       └── project_completion_summary.txt
│
├── scripts/
│
├── .gitignore
└── README.md

Tools & Technologies

Python: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

SQL: SQLite (via Python)

Power BI: Executive dashboards and KPI reporting

Machine Learning: Logistic Regression, feature engineering

Version Control: Git & GitHub

Data Cleaning & Feature Engineering

Removed duplicates and handled missing values

Optimized data types for performance

Treated outliers using IQR-based capping

Engineered:

Time-based features

Customer-level metrics

Product-level metrics

Validated data quality before analysis

Exploratory Data Analysis (EDA)

Key insights generated through EDA:

Revenue and profit distribution analysis

Monthly and seasonal sales trends

Regional and category-wise performance

Customer purchase frequency patterns

Identification of top customers and products

Customer Analytics
Customer Segmentation

Customers segmented based on order frequency:

Loyal Customers

Repeat Customers

One-time Customers

Customer Lifetime Value (CLV)

Estimated customer lifetime value using purchase behavior

Identified high-value customers contributing disproportionately to revenue

Retention Analysis

Cohort-based retention analysis

Strong retention among repeat and loyal customers

Predictive Modeling
Objective

Predict whether a customer is likely to make a repeat purchase.

Approach

Target variable: Repeat Customer (binary)

Features: Orders, revenue, discounts, recency, product diversity

Model: Logistic Regression

Evaluated using accuracy and classification metrics

Business Use Case

Targeted retention campaigns

Customer prioritization

Marketing efficiency improvement

SQL Analysis

SQL (via SQLite) was used to:

Perform aggregation-based business analysis

Analyze customer revenue concentration

Validate retention and CLV insights

Demonstrate database-level analytics capability

Power BI Dashboards

Two executive-ready dashboards were developed:

Executive Overview

Total Sales, Profit, Orders, Customers

Monthly sales trend

Sales by region

Interactive slicers for time, region, and category

Customer Intelligence

Customer segment distribution

Retention vs churn

Top customers by revenue

Customer behavior insights

Dashboard images are available in the assets/ folder.

Key Business Insights

A small group of loyal customers generates a majority of revenue

Repeat customers have significantly higher lifetime value

Clear seasonality exists in sales trends

Regional performance varies, indicating optimization opportunities

Retention is strong, while new customer acquisition can be improved

Future Enhancements

Deploy predictive model for live customer scoring

Integrate model outputs into CRM systems

Automate model retraining

Extend dashboards with real-time data sources

Author

Nupur Mirje
Data Analytics | Business Analytics | Python | SQL | Power BI

Final Note

This project emphasizes correctness, business reasoning, and end-to-end analytics workflows, reflecting how analytics is practiced in real organizations.