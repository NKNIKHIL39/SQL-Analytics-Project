🛍️ Retail Superstore SQL Analytics Project
📘 Business Summary
The goal of this project was to analyze the sales and returns data of a retail superstore to uncover actionable insights that can help:

Reduce losses

Improve profitability

Understand customer behavior

Key business problems addressed:

🔄 Optimizing product returns to reduce operational costs

📉 Identifying low-performing products to improve margins

🧑‍🤝‍🧑 Segmenting customers for targeted marketing

🌍 Analyzing region-level performance to guide budget allocation

💸 Evaluating discount strategies to prevent margin erosion

“By analyzing return patterns and discount strategies, we identified products contributing to negative margins, allowing the business to make pricing and catalog decisions.”

🧠 What I Learned
Building a complete end-to-end data pipeline using Azure SQL and Power BI

Writing advanced T-SQL queries using:

CTEs

Window functions

Subqueries

Aggregations

Date functions

Designing modular and reusable SQL logic via views and stored procedures

Modeling transactional data into decision-ready metrics and KPIs

Applying best practices in Power BI dashboard storytelling

Recognizing negative profit drivers (e.g., returns, over-discounting)

Segmenting customers for value-driven retention strategies

🔧 Tools & Techniques Used
Tool / Technology	Purpose
Azure SQL Database	Hosted and managed the cleaned datasets
SQL Server Management Studio (SSMS)	Wrote and tested SQL queries
T-SQL	Performed aggregations, joins, cleaning, logic
Power BI Desktop	Built interactive dashboards and KPIs
Power BI Service (optional)	Enabled cloud-based sharing and refresh scheduling
Excel / CSV	Provided raw data source (Superstore Orders & Returns)
🧪 Real Business Insights
📊 These were visualized in a Power BI dashboard with KPIs, filters, and drill-through capabilities.

35% of returns came from just 3 product sub-categories

Discounts over 25% led to -20% average profit margins

The top 10% of customers drove 60% of profits — ideal for loyalty programs

Returned orders had an average 3x lower margin than non-returned

Western region outperformed others by 15% in net profit — budget allocation can be adjusted accordingly

🛠️ Data Engineering Pipeline
✅ End-to-End Flow:
Raw Data Ingestion

CSV files (Superstore Orders & Returns)

Loaded into Azure SQL Database

Data Transformation

SQL logic developed in SSMS / Azure Data Studio

Includes joins, CTEs, window functions, filters

Data Modeling

Built SQL views and reusable queries for Power BI

Modular structure for maintainability

Business Intelligence Reporting

Connected Power BI to Azure SQL

Developed dashboards with KPIs, visuals, filters

Automation & Deployment

Power BI report refresh scheduled via Power BI Service

Fully cloud-based solution with daily refreshes

📊 Dashboard Design Highlights
A Power BI dashboard was created to support business storytelling and data exploration:

Summary KPI Cards: Sales, Profit, Return Rate, Customer Count

Filters & Slicers: Region, Category, Segment

Visuals: Bar charts, line graphs, pie charts, matrix tables

Drill-Through: Region ➝ Customer ➝ Product

Bookmarks: Seamless navigation between dashboard views

🚀 Real-World Impact
This project reflects a real corporate analytics workflow where:

Data is stored in the cloud and accessed using enterprise SQL tools

Complex business questions are answered through data-driven insights

Stakeholders get timely and interactive Power BI dashboards

Data refresh is automated for real-time decision making

✅ This project is a complete showcase of data engineering, analytics, and business intelligence, ideal for roles in SQL, BI, and Data Analysis.
