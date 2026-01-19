Sales Analysis Dashboard – Power BI
📌 Project Overview

This project focuses on building an interactive Sales Dashboard in Power BI to analyze sales performance, profit, discounts, and customer behavior across different dimensions such as product, customer, promotion, city, and time.
The dashboard helps stakeholders make data-driven decisions by identifying trends, top-performing products, and profit-impacting factors.

🗂️ Data Model & Tables Used
🔹 Fact Table

Order ID

Date

Customer ID

Product ID

Promotion ID

Units Sold

Total Sales

Net Sales

Discount

Discount Percentage

Profit

Price Per Unit

🔹 Dimension Tables

1. Date Tables

Date Table 1 (Primary Date)

Date Table 2 (Comparison Date for period analysis)

2. Dim Customers

Customer ID

Customer Name

City

State

Pincode

Email ID

Phone Number

3. Dim Product

Product ID

Product Name

Product Line

Price Per Unit

4. Dim Promotion

Promotion ID

Promotion Name

Ad Type

Coupon Code

Discount Percentage

Price Reduction

5. Measures Table

Quantity Sold

Sum of Net Sales

Total Profit

⚙️ Tools & Technologies Used

Power BI (Data Modeling, DAX, Visualization)

Power Query (Data Cleaning & Transformation)

DAX Measures (KPIs & Calculations)

Star Schema Data Model

Excel / CSV / Flat Files as data source

📈 Key Dashboard Features
1️⃣ Top & Bottom 5 Analysis

Top 5 and Bottom 5 Products by Sales, Profit, and Quantity Sold

2️⃣ Sales Trend Analysis

Daily

Monthly

Quarterly

Yearly trends to identify seasonality and growth patterns

3️⃣ Sales vs Profit Relationship

Visual comparison to identify high-revenue but low-profit products

4️⃣ Period Comparison (Dynamic)

Compare Sales / Profit / Quantity Sold between any two selected periods using Date Table 1 & 2

5️⃣ Discount Analysis

Average discount offered across different discount categories

6️⃣ Total Orders KPI

Total number of orders placed

7️⃣ Order-Level Analysis

Detailed table showing:

Sales

Profit

Discount

Net Sales

Units Sold

Fully filterable by:

Product

Date

Customer ID

Promotion

8️⃣ City-wise Sales Analysis

Sales performance across different cities for regional insights

🎯 Business Impact

Helped identify high-profit and low-profit products

Improved visibility into discount effectiveness

Enabled management to track sales trends over time

Supported better promotion and pricing decisions

Reduced manual reporting effort with automated dashboard

📸 Dashboard Preview

(Add screenshots of your Power BI dashboard here)

🚀 How to Use

Download the .pbix file from the repository

Open it in Power BI Desktop

Refresh data (if source is connected)

Use slicers to interact with the dashboard
