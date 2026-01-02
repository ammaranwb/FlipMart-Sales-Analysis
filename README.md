📊 FlipMart Sales Analysis | Power BI Dashboard
📌 Project Overview

FlipMart is a global retail and e-commerce company aiming to analyze historical sales data to identify growth opportunities, understand customer behavior, and improve operational efficiency across regions.

In this project, I built an end-to-end Power BI dashboard that transforms raw transactional data into actionable business insights across sales performance, customer segmentation, and product analysis.

🎯 Business Objectives

Track sales, cost, and profit trends over time

Measure year-over-year (YoY) growth and average order value (AOV)

Identify top customers, repeat buyers, and high-value segments

Analyze product categories, sub-categories, and best-selling products

Evaluate regional performance and profit distribution by country

🗂 Dataset Description

The dataset contains 51,290 sales records with the following information:

Order Details: Order ID, Order Date, Ship Date, Shipping Mode

Customer Data: Customer ID, Customer Name, Segment, Country

Product Data: Product ID, Category, Sub-Category, Product Name

Metrics: Quantity, Shipping Cost, Cost, Sales

🔧 Data Preparation & Transformation

Performed using Power Query:

Data quality checks (nulls, errors, duplicates)

Removed blank rows and unnecessary columns

Created separate Customer and Product tables from the sales data

Removed duplicates from all tables

Ensured correct data types for dates and numeric fields

🧱 Data Modeling

Implemented a Star Schema with:

Fact Table: Sales

Dimension Tables: Customers, Products, Calendar

Created a Calendar Table using DAX for time-based analysis

Established clean relationships to support scalable analytics

📐 Key DAX Measures

Total Sales

Total Cost

Profit

Average Order Value (AOV)

Year-over-Year (YoY) Sales Growth

Customer and product performance metrics

📊 Dashboard Structure

The Power BI report contains three interactive pages:

1️⃣ Sales Analysis

Sales, cost, and profit trends over time

Monthly and yearly growth analysis

Sales vs profit correlation

2️⃣ Customer Analysis

Total and repeat customers

Top-performing customers

Sales by customer segment and country

3️⃣ Product Analysis

Product and category performance

Most profitable and best-selling products

Top products by order count

Each page includes KPI cards, charts, and interactive filters for business users.

💡 Key Insights

Identified top-performing regions and customer segments driving revenue

Highlighted repeat customers contributing significantly to sales

Discovered high-profit product categories and best-selling products

Revealed uneven profit distribution across countries, enabling targeted strategy

🛠 Tools & Technologies

Power BI

Power Query

DAX

Data Modeling (Star Schema)

Business Intelligence & Analytics

📁 Files Included

FlipMart-Sales-Analysis.pbix – Power BI dashboard file

FlipMart-Sales-Analysis-Dashboard.pdf – Exported dashboard for easy viewing

screenshots/ – Dashboard screenshots
