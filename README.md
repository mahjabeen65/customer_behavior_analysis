# customer_behavior_analysis
Customer Shopping Behavior Analysis

Analysis of 3,900 customer transactions to uncover spending patterns, customer segments, and subscription behavior — using Python for data cleaning/EDA, SQL (PostgreSQL) for business queries, and Power BI for an interactive dashboard.

Dataset


3,900 rows, 18 columns
Demographics, purchase details, and shopping behavior fields
Cleaned missing Review Rating values via category median


Workflow


Python — Cleaned data, standardized columns, engineered age_group and purchase_frequency_days
SQL — Answered 10 business questions (revenue by gender/age, top products, customer segmentation, subscriber trends, etc.)
Power BI — Built a dashboard with KPIs, category/age revenue breakdowns, and subscription filters


Key Insights


Male customers generated ~2x the revenue of female customers
Loyal customers make up the majority of the base (3,116 of 3,900)
Young Adults are the top revenue-generating age group
Non-subscribers drive more total revenue than subscribers


Recommendations


Boost subscription incentives
Launch loyalty programs for repeat buyers
Reassess discount-heavy product lines
Target marketing toward high-revenue age groups


Tools

Python (pandas) · PostgreSQL · Power BI

Structure

data/          # datasets
notebooks/     # Python EDA
sql/           # SQL queries
dashboard/     # Power BI file
