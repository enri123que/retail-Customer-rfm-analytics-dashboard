# retail-Customer-rfm-analytics-dashboard
An end-to-end data pipeline (SQL, Python, Power BI) evaluating a 1M+ row retail dataset to segment customers using RFM analysis.

End-to-End Retail & RFM Customer Analytics Dashboard
Project Overview
This project establishes an end-to-end data pipeline that processes over 1,033,000 transaction records to clean, model, and segment customers for an e-commerce platform. Using SQL for database engineering, Python (Pandas) for statistical analysis, and Power BI for executive reporting, the project uncovers hidden purchasing behaviors and tracks customer churn risks.

Tech Stack & Skills Demonstrated
Database Engineering (SQL): Combined multi-year transactional schemas, eliminated duplicate logs, handled empty values, and generated clean relational outputs.
Data Science (Python): Developed data pipelines utilizing pandas.qcut to evaluate Recency, Frequency, and Monetary scores across 5 distinct quintiles.
Business Intelligence (Power BI): Designed a high-performance star-schema data model and built dynamic visual cards tracking Total Customers, Revenue, and Churn % (50.9%).
Repository Architecture
/scripts: Production-ready SQL optimization scripts.
/notebooks: Exploratory data analysis (EDA) and RFM feature engineering.
/dashboard: High-resolution layouts and tracking templates.
Strategic Business Insights Found
Churn Mitigation: Identified that 50.9% of the customer base has crossed the critical 90-day inactivity threshold (isChurned = True).
Value Distribution: Determined that "Champions" and "Loyal" segments account for the vast majority of the company's £17M total revenue.
Geographic Concentrations: Discovered that despite global distribution (e.g., Australia, France, Germany), the United Kingdom remains the primary commercial driver.
