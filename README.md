Blinkit Power BI Dashboard – Sales Analysis
📌 Project Overview

This Power BI project presents an interactive sales and performance dashboard for Blinkit, providing business insights into sales trends, outlet performance, customer preferences, and product categories.
The dashboard enables stakeholders to make quick, data-driven decisions using visual analytics.

🎯 Business Objectives

Monitor total sales and revenue trends

Analyze outlet performance by type, size, and location

Identify top-selling product categories

Understand customer ratings and buying behavior

Compare Low Fat vs Regular product performance

🛠 Tools & Technologies

Power BI Desktop

Power Query – Data cleaning & transformation

DAX – Measures & calculated columns

Excel / CSV – Data source

📂 Dataset Used

Blinkit sales dataset (blinkit_data.csv)

Cleaned using Power Query Editor

Handled missing values and standardized categories

🧮 Key DAX Measures
Total Sales = SUM(Blinkit[Item_Outlet_Sales])

Average Sales = AVERAGE(Blinkit[Item_Outlet_Sales])

Total Items = DISTINCTCOUNT(Blinkit[Item_Identifier])

Average Rating = AVERAGE(Blinkit[Rating])

📊 Dashboard Pages
🟢 1. Sales Overview

Total Sales

Average Sales

Total Items

Average Rating

Sales trend by outlet establishment year

🟢 2. Product Analysis

Sales by Item Type

Fat Content comparison

Item visibility impact on sales

🟢 3. Outlet Performance

Sales by Outlet Type

Sales by Outlet Size

Location-wise sales (Tier 1, 2, 3)

🟢 4. Customer Insights

Rating distribution

Top-rated product categories

Sales vs Ratings correlation

📈 Key Insights

🏆 Supermarket Type 1 outlets contribute the highest sales

🥗 Low Fat products outperform Regular products

📍 Tier 3 locations generate maximum revenue

⭐ Products with higher ratings show better sales performance

🎨 Visuals Used

KPI Cards

Bar Charts

Pie & Donut Charts

Line Charts

Slicers (Outlet Type, Location, Item Type)

Matrix Tables
