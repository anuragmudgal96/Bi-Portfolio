# Ecommerce Sales Analysis Dashboard
### Project Objective (Business Problem):
The management team needs a way to track KPIs (sales, revenue, profit, returns), compare regional performance, analyze product-level trends, and identify high-value customers.
## KPIs & Metrics:
- Total Revenue, Total Profit, Total Orders, Return Rate
- Revenue Trend Month Wise, Top 10 Products by Orders
- Most Ordered Product, Most Returned Product
- Orders distribution based on Geography
- Monthly order/Monthly Revenue/Monthly Profit Vs. Target
- Product Return Trend Month Wise
- Order distribution by Income Level and Occupation
- Top Customer (by revenue)
## Data Source & Transformation:
- Data was pulled from SQL Server (Customer Lookup, Product Lookup, Product Subcategories, Return Data, Territory Lookup, and sales data of 2020-2022)
- Used Power Query to clean missing/null values, standardize formats, and append sales data tables.
- Derived new columns and data type casting.
- Utilized data profiling to handle the errors and null values.
- Build a realtional data model connected foreign keys of fact table with the primary key of dimension tables.
- datasets [files](https://github.com/anuragmudgal96/Bi-Portfolio/tree/main/Ecommerce%20Sales%20Analysis%20Dashboard/datasets)
  
<img width="1492" height="723" alt="Screenshot 2025-09-19 194342" src="https://github.com/user-attachments/assets/dfa59b04-b624-4d5a-a76d-3a3a30d2ce47" />


## DAX & Advanced Features: 
- Used DAX Measures to calculate % of all returns, YTD Revenue, Price Adjustment (%) Value, 10-day Rolling Revenue, Implemented Dynamic high value customer.
- Created Drill-through pages for deep-diving into product-level and region insights.
- Used bookmark and slicer for interactive filtering.
- DAX [Measures sheet](https://github.com/anuragmudgal96/Bi-Portfolio/blob/main/Ecommerce%20Sales%20Analysis%20Dashboard/measures.dax)

## Dashboard:
Dashboard [Link](https://github.com/anuragmudgal96/Bi-Portfolio/blob/main/Ecommerce%20Sales%20Analysis%20Dashboard/Ecommerce%20Sales%20Analysis%20Dashboard.pdf)

<img width="1301" height="727" alt="Screenshot 2025-09-19 194912" src="https://github.com/user-attachments/assets/10dcd7e5-c399-4247-9932-28f3116fcb48" />


## Learning Outcomes:
- Connect and transform the raw data using power query
- Build a relational data model
- Create calculated columns and measures with DAX
- Design an interactive dashboard to visualize the data, enabling users to drill down into key insights.
- Publish Power BI report to the Power BI service.
