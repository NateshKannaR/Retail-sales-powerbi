📊 Retail Sales Performance Dashboard – Power BI
📌 Project Overview

This project presents a Retail Sales Performance Dashboard built using Microsoft Power BI.
The dashboard helps analyze sales, profit, and performance across regions, categories, products, and time, enabling data-driven business decisions.

It is designed for business stakeholders, analysts, and students to quickly understand key retail metrics and trends.

🎯 Problem Statement

Retail businesses often store sales data in spreadsheets, making it difficult to:

Track overall sales and profit performance

Compare performance across regions and categories

Identify high-profit and low-profit products

Monitor profit margins and trends over time

This dashboard solves these challenges by providing interactive visual insights in one place.

📂 Dataset Description

The dataset includes the following key fields:

Order Date

Region (East, West, North, South)

Category (Electronics, Office Supplies)

Product Name

Sales

Profit

Quantity

Segment (Consumer, Corporate, Small Business)

🧹 Data Preparation

Data was cleaned and prepared in Power Query Editor:

Removed extra spaces from column names

Converted date fields to proper Date format

Ensured Sales and Profit columns are numeric

Validated data consistency and removed errors

🧮 DAX Measures Used

The following calculated measures were created:

Total Sales = SUM(Sales[Sales])

Total Profit = SUM(Sales[Profit])

Total Orders = COUNT(Sales[Order ID])

Average Sales = AVERAGE(Sales[Sales])

Profit Margin % = DIVIDE([Total Profit], [Total Sales])

📈 Dashboard Visuals

The dashboard includes:

KPI Cards

Total Sales

Total Profit

Profit Margin %

Charts

Total Sales by Region

Total Profit by Category

Sales Count by Category

Sales Trend by Date

Profit Margin by Product

Maps

Profit and Sales distribution by Region

Slicers

Category

Region

Segment

These visuals allow users to drill down and filter data interactively.

🔍 Key Insights

Certain regions consistently generate higher sales

Electronics category contributes more to profit

Some products have high sales but low profit margins

Profit margin varies significantly across categories

🛠 Tools & Technologies

Microsoft Power BI

Power Query

DAX (Data Analysis Expressions)

Excel (Data Source)

🚀 How to Use

Download the .pbix file from this repository

Open it using Power BI Desktop

Use slicers to filter by region, category, or segment

Hover over visuals to explore insights

📌 Use Cases

Retail performance monitoring

Sales & profit analysis

Business intelligence learning project

Power BI portfolio showcase

👤 Author

Natesh
Power BI | Data Analytics Enthusiast

⭐ If you like this project

Give it a ⭐ on GitHub and feel free to fork or improve it!
