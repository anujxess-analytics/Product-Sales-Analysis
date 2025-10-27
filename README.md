🏷️ Title

Product Sales Analysis Dashboard – Power BI Project

📰 Headline

An interactive and data-driven Power BI dashboard designed to analyze product sales, payment modes, and regional performance using real-world business datasets.

🧾 Short Description / Purpose

The purpose of this project is to provide a comprehensive analysis of product sales performance across multiple dimensions — including product categories, states, payment types, and managers.
This dashboard helps in identifying key business insights such as:

1. Which products generate the highest sales revenue
2. Which payment methods customers prefer most
3. How sales vary across different regions and managers
4. The goal is to transform raw data into meaningful insights that can drive strategic decision-making and business growth.

🧰 Tech Stack

Tool / Technology	Purpose
Power BI Desktop -	For data modeling, visualization, and report creation
Power Query -	For data cleaning and transformation
DAX (Data Analysis Expressions) -	For creating calculated measures and KPIs
Excel -	For raw data storage and structuring
Star Schema Data Modeling -	For efficient relationship building between fact and dimension tables

📊 Data Source

This project uses multiple Excel files as data sources:
Sales_Data.xlsx – Contains sales transactions with quantity, amount, and manager info.
ProductTable.xlsx – Details of each product with ID and name.
SubProductTable.xlsx – Information about sub-products linked to main products.
PaymentTable.xlsx – Payment modes such as UPI, Credit Card, Cash, etc.
StateTable.xlsx – State names for regional analysis.

All these tables are connected in Power BI through relationships using a Star Schema model.

🌟 Features & Highlights

📁 Data Modelling (Star Schema):
Connected multiple tables (Sales, Product, SubProduct, Payment, State) using one-to-many relationships.

⚙️ DAX Measures & KPIs:
Created measures like Total Sales, Average Sales, and Quantity Sold to analyze performance effectively.

📈 Interactive Visualizations:
• KPI Cards showing key metrics
• Pie Charts for Payment Distribution
• Bar Charts for Top Products and Sub-products
• Map Visuals for State-wise Sales Analysis
• Filters and Slicers for dynamic analysis (Month, Manager, State)

🧠 Business Insights Derived:
• Identified top-performing products and regions
• Determined most used payment modes by customers
• Highlighted performance contribution by different managers
• Simplified decision-making through visual insights

💡 User-Friendly Design:
The dashboard layout focuses on clarity, interactivity, and data storytelling — allowing even non-technical users to explore the data intuitively.# Product-Sales-Analysis

Screenshot

[Dashboard Preview](https://github.com/anujxess-analytics/Product-Sales-Analysis/blob/main/Product%20Sales%20Analysis%20Dashboard.png)
