# Sales-Dashboard Analysis

Project Overview

The Sales Data Analysis Dashboard is an interactive Power BI project designed to analyze business sales performance across products, regions, time periods, and customer segments.

This dashboard enables stakeholders to monitor key performance indicators, identify high-performing products, evaluate the impact of discount strategies, and understand geographic sales distribution. By transforming raw sales data into meaningful visual insights, the dashboard supports data-driven business decision-making.

📌 Business Problem

Businesses often collect large volumes of sales data but struggle to convert that data into actionable insights. Decision-makers require clear answers to critical questions such as:

Which products generate the most revenue?
Which cities or regions perform best in terms of sales?
How do discounts impact profitability?
How does sales performance change over time?

Without a structured analytical dashboard, identifying these insights can be time-consuming and inefficient.

This Power BI Sales Dashboard solves this challenge by providing an interactive platform where users can explore sales data through dynamic visuals and filters.

🛠 Tools & Technologies Used

The project was developed using the following tools and technologies:

Power BI Desktop – Data visualisation and dashboard creation
Power Query – Data cleaning and transformation
DAX (Data Analysis Expressions) – Creating calculated measures
Star Schema Data Modelling – Optimised data relationships
Excel / CSV Dataset – Source data
📂 Data Preparation

The following steps were followed during the data preparation process:

Imported the dataset into Power BI Desktop.
Opened Power Query Editor to perform data transformation.
Checked column quality, distribution, and profile for data validation.
Removed or handled missing values where necessary.
Verified and corrected data types across all columns.
Created a Date Table to support time-based analysis.
Established relationships between tables to build a Star Schema data model.
Optimised the data model for efficient querying and reporting.
📈 Key DAX Measures

Several important DAX measures were created to support analysis in the dashboard:

Total Sales

Total Sales = SUM(Sales[Sales Amount])

Total Profit

Total Profit = SUM(Sales[Profit])

Total Quantity Sold

Total Quantity = SUM(Sales[Quantity])

Average Discount

Average Discount = AVERAGE(Sales[Discount])

Net Sales

Net Sales = [Total Sales] - ([Total Sales] * [Average Discount])

These measures help calculate important KPIs used throughout the dashboard.

📊 Dashboard Screenshots Used in Various Analyses

The dashboard contains multiple visual components used to analyze different aspects of business performance.

1. Dashboard Overview

Visualizations Used

- KPI Cards
- Clustered Bar Chart
- Slicers (Filters)

Purpose

KPI Cards display key business metrics, including:

Total Sales
Total Profit
Total Orders
Total Quantity Sold

The Clustered Bar Chart helps compare sales performance across different product categories or segments.

Slicers allow users to filter the dashboard by:

Date
Product
Customer
Promotion Category

2. Sales Trend Analysis

Visualisation Used

- Line Chart

Purpose

The Line Chart shows how sales change over time. It helps analyze sales trends at different time intervals such as:

Daily
Monthly
Quarterly
Yearly

This visualization helps identify:

Growth patterns
Seasonal trends
Revenue fluctuations.

3. Top and Bottom Products Analysis

Visualization Used

- Clustered Bar Chart
- Horizontal Bar Chart

Purpose

These charts highlight the Top 5 and Bottom 5 products based on:

Sales
Profit
Quantity Sold

The bar chart makes it easy to compare product performance and quickly identify best-selling and underperforming products.

4. Sales vs Profit Analysis

Visualization Used

- Scatter Plot

Purpose

The Scatter Plot visualizes the relationship between Sales and Profit.

Each point represents a product or transaction, allowing users to identify:

High sales but low profit products
Highly profitable product categories
Potential pricing or discount issues.

5. Discount Analysis

Visualization Used

- Bar Chart
- Column Chart

Purpose

These charts analyze the average discount distribution across different categories or products.

They help identify:

Which discount levels drive more sales
Whether heavy discounts impact profit margins.

6. Geographic Sales Analysis

Visualization Used

- Map Visualization
- Filled Map

Purpose

The Map Visualization displays sales distribution across different cities or regions.

This helps businesses understand:

Regional sales performance
High-demand markets
Geographic expansion opportunities.

7. Detailed Transaction Table

Visualization Used

- Table Visualization
- Matrix Table

Purpose

These visuals provide detailed transactional data, including:

Sales Amount
Profit
Discount
Quantity Sold
Customer Information

They allow users to perform deeper analysis and drill down into individual transactions.

🔍 Key Insights from the Dashboard

From the analysis performed in the dashboard, several insights were identified:

A small number of products contribute significantly to total revenue.
Certain cities generate higher sales compared to others.
High discount rates increase sales volume but may reduce profitability.
Sales performance shows noticeable seasonal trends.
Product performance varies across different geographic markets.

These insights help businesses improve strategic planning and operational efficiency.


8 Screenshots/Demos
Dashboard preview : https://github.com/rahul251296/Sales-Dashboard/blob/main/Sales%20Overview.PNG


🎯 Conclusion

The Sales Data Analysis Dashboard provides a comprehensive view of business performance by combining sales metrics, product insights, and geographic analysis in a single interactive platform.

Using Power BI's powerful data modeling and visualization capabilities, this project transforms raw sales data into actionable business intelligence. The dashboard enables organisations to:

Monitor key performance indicators
Identify high-performing products
Understand regional sales patterns
Evaluate the impact of discounts on profitability
Make informed, data-driven decisions

Overall, the dashboard demonstrates how modern business intelligence tools can significantly improve visibility into business operations and support strategic decision-making.


Author
Rahul Soni
