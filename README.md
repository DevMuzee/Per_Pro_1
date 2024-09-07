# Exec_Sales_Anal
Comprehensive Sales Dashboard for Bike Sales Company

## Table of Content
- [Project Overview](#project-overview) 📑
- [Tools Used](#tools-used) 🧰
- [Data Cleaning](#data-cleaning) 
- [Exploratory Data Analysis](#exploratory-data-analysis) 📖
- [Data Analysis](#data-analysis)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

## Project Overview
This project focused on creating a comprehensive sales dashboard for the executive team of a bike sales company. The dashboard was developed by extracting relevant data from the company’s SQL database, followed by using Excel for data cleaning and initial analysis. Pivot tables were utilized to design a dynamic Excel dashboard, which was later connected to Tableau for creating the final interactive sales dashboard. The project aimed to provide real-time insights into sales performance, customer trends, and inventory management to support strategic decision-making.

## Tools Used
- Database: SQL (for data extraction) 💻
- Data Cleaning and Analysis: Excel
- Visualization: Tableau 
- Pivot Tables: Excel for dynamic data analysis
- IDE: Excel, SQL Workbench, SSMS, Tableau 💻 🖥️

## Data Cleaning
- The dataset was extracted from the company's SQL database using custom SQL queries to gather relevant sales data such as bike models, sales volumes, customer demographics, and inventory levels.
- The imported data in Excel underwent the following cleaning steps:
  - Removal of duplicates and irrelevant entries.
  - Addressing missing values by either imputing with mean values or removing incomplete records.
  - Formatting of date and currency fields for consistency.
  - Data normalization for specific fields like bike categories and customer regions.
- Data was then structured in a format suitable for Pivot Table analysis.

## Exploratory Data Analysis 
- Using Excel’s Pivot Tables, initial data exploration was carried out:
  - Breakdown of sales by region, bike model, and time period.
  - Identification of high-performing and low-performing bike models.
  - Analysis of customer demographics and purchasing patterns.
  - Visualization of sales trends over time using line charts and bar graphs.
- Key performance indicators (KPIs) such as revenue per year, revenue per month, per store, per category, per sales rep, and top customers were computed.

## Data Analysis
- SQL Queries were used to filter, join, and aggregate relevant data, providing a clear understanding of sales performance and trends.
- Excel Dynamic Dashboard: Created with Pivot Tables, offering real-time updates when new data was input. The dashboard included slicers and filters for executives to interact with the data based on specific criteria such as region, time period, and bike category.
- Tableau Dashboard: Excel data was connected to Tableau for advanced visualizations and interactivity. Key features of the Tableau dashboard included:
  - Sales trend analysis using series of graphs.
  - Interactive filters allowing the executive team to drill down into specific segments.
  - KPIs like total revenue, top-selling models, and customer retention rate.

## Recommendations
- Targeted Marketing: Based on sales trends, marketing efforts should focus on high-demand regions and top-selling bike models to optimize revenue.
- Inventory Management: Insights from the dashboard suggest optimizing inventory for the most popular bike models to prevent stock shortages and reduce excess stock of slower-selling models.
- Customer Segmentation: By analyzing customer demographics, the company can tailor its product offerings and promotions to better align with customer preferences in specific regions.
- Sales Performance Optimization: Regular updates to the dashboard will enable the executive team to monitor and adjust sales strategies in real-time, ensuring continuous performance improvement.

## Limitations
- Data Freshness: The dashboard relies on periodic data imports from SQL to Excel, which may lead to slight delays in real-time insights.
- Static Pivot Tables: While the Excel dynamic dashboard provides interactivity, it is limited to the scope of data imported, meaning that any new data requires re-importing and re-refreshing the entire Excel sheet.
- Limited Scalability: As the data grows in size, Excel’s capacity to handle large datasets becomes limited, potentially affecting performance. Tableau offers more flexibility for large datasets but still relies on Excel as the intermediary in this case.
- Manual Updates: The need to manually update the Excel dataset for both the Excel and Tableau dashboards might introduce errors or inconsistencies if not done regularly and correctly.
- SQL Complexity: The depth of analysis is restricted by the complexity of the SQL queries written. More sophisticated queries could extract deeper insights, but require advanced SQL skills.

