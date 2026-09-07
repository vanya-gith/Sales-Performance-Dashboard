# 📊 Sales Performance Dashboard | Power BI
## 1. Project Overview
This project is an interactive Sales Performance Dashboard built in Microsoft Power BI to analyze sales performance, profitability, regional contribution, product performance, customer segments, returns, and monthly sales trends.
The objective of this project was to transform transactional sales data into a structured, interactive, and decision-ready business intelligence solution that enables users to monitor KPIs, identify trends, compare performance, and explore detailed business insights.


## 2. Key Insights
**West** was the top-performing region with ₹16.25M in sales, contributing approximately **25.21%** of total sales.
**Electronics** was the dominant category, generating ₹50.66M and contributing approximately **78.57%** of total sales.
**Consumer** was the leading customer segment with ₹36.98M, contributing approximately **57.36%** of sales.
**Laptop Pro** was the highest-selling product with approximately ₹14.02M in sales.
**July** recorded the highest monthly sales at approximately ₹6.43M.
🔹Overall sales increased by approximately **4.79% YoY**, while profit increased by approximately **4.83% YoY**.

## 3. Data Source
Excel-based transactional sales dataset
Includes **Fact Sales, Customers, Products, Stores, Date, and Sales Target** tables
Data covers **2024–2025**
Approximately **4,500 sales transactions**


## 4. Technical Implementation
Power Query: Data cleaning, transformation and ETL
DAX: KPI measures, profitability, return rate and time-intelligence calculations
Data Modeling: Star-schema based model using fact and dimension tables
Row-Level Security (RLS): Region-based secure data access
Interactive Features: Slicers, drill-through, report page tooltips and bookmarks
Visualization: KPI cards, monthly trends, regional analysis, category analysis, customer segmentation and product performance.

## 5. Data Preparation & Power Query
Power Query was used as the ETL layer to prepare the source data before loading it into the Power BI model.
Key activities included:

- Data type validation
- Data cleaning and transformation
- Preparing fact and dimension tables
- Handling and standardizing fields
- Preparing the date dimension for time-intelligence analysis
- Structuring the data for reporting and DAX calculations

## 6. Data Modeling
A **star-schema based data model** was implemented with 'FactSales' as the central fact table and dimension tables surrounding it.
The model allows filters from dimensions to flow into the transactional sales table and provides consistent calculations across the dashboard.
Show what the model looks like :- ![DataModel].(https://github.com/vanya-gith/Sales-Performance-Dashboard/blob/main/Data%20Model%20Snapshot.png)

## 7. Row-Level Security (RLS)
The project also implements Row-Level Security (RLS) for region-based access.
The security model allows different users to view only the sales data associated with their assigned region.
For example: West Manager   → West data
North Manager  → North data
South Manager  → South data
East Manager   → East data
Central Manager → Central data
Dynamic user identification is handled using: USERPRINCIPALNAME()
This demonstrates how Power BI can be used not only for visualization but also for controlled and role-based business reporting.

## 8. Advanced Power BI Features
The dashboard includes several interactive and advanced Power BI features:

Drill-through – Dedicated Region Details page for detailed regional analysis
Bookmarks – Used for navigation and Reset Filters functionality
Report Page Tooltips – Provides additional contextual information on hover
Dynamic Slicers & Filters – Allows users to interactively analyze different business dimensions
Interactive Visualizations – KPI cards, monthly trends, regional analysis, category analysis, customer segmentation, and product performance

## 9. Business Objectives
The dashboard was designed to answer key business questions such as:

How much total sales and profit are being generated?
How is the business performing compared with the previous year?
Which region contributes the highest sales?
Which product category generates the most revenue?
Which products are the top sellers?
Which customer segment contributes the most sales?
How do sales change month by month?
What is the current profit margin?
What is the return rate?
Can users securely access only the data relevant to their region?

## 10. Key Takeaways
The analysis highlights several important business patterns:

*West is the strongest regional contributor.
*Electronics is the primary revenue-driving category.
*Consumer contributes the largest share of sales.
*A small number of top products contribute significantly to overall revenue.
*Sales and profitability improved year over year.
The dashboard provides an interactive way to monitor business performance rather than relying only on static reports.

## 11. Project Outcome
This project demonstrates my practical ability to work across the complete Power BI reporting workflow:

**Raw Data → Power Query → Data Cleaning → Data Modeling → DAX → KPI Development → Visualization → Interactivity → RLS → Business Insights**

The project strengthened my hands-on skills in Power BI, DAX, Power Query, data modeling, business intelligence, and analytical storytelling.

Dashboard Snapshot - ![Dashboard].(https://github.com/vanya-gith/Sales-Performance-Dashboard/blob/main/Snapshot%20Of%20The%20Dashboard.png)
