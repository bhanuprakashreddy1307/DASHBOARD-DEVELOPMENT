# DASHBOARD-DEVELOPMENT

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : KONTHAM BHANU PRAKASH REDDY

*INTERN ID* : CT12UYL

*DOMAIN* : DATA ANALYTICS

*DURATION* : 8 WEEKS

*MENTOR* : NEELA SANTOSH

*DESCRIPTION* :
Introduction
In today’s competitive business environment, data-driven decision-making is crucial for companies like Adidas to stay ahead. Analyzing sales performance enables businesses to identify trends, optimize strategies, and make informed business decisions. Power BI, a powerful business intelligence tool by Microsoft, allows users to create interactive dashboards for data visualization and analysis. This article outlines the process of developing a Power BI dashboard for Adidas' 2021 sales analysis, covering data collection, transformation, visualization, and insights.

Data Collection and Preparation
The first step in creating a Power BI dashboard is gathering and preparing the data. The Adidas sales dataset for 2021 typically includes:

Transaction Data: Sales order numbers, dates, and revenue details.

Product Data: Information about Adidas products such as categories, models, and pricing.

Customer Data: Customer demographics, including location, age, and purchase preferences.

Geographical Data: Regional sales performance across different countries or states.

After importing the dataset into Power BI, the next step is data transformation using Power Query Editor. This involves:

Cleaning null or duplicate values.

Standardizing date formats.

Merging multiple datasets (e.g., joining customer and transaction data).

Creating calculated columns (e.g., profit margin, total revenue per category).

Data Modeling and DAX Calculations
Once the data is clean, a relational data model is built. The model follows a star schema, where fact tables (sales transactions) are linked to dimension tables (products, customers, regions). This structure enhances performance and ensures efficient querying.

Using DAX (Data Analysis Expressions), we create measures to generate insights:

Total Sales = SUM(Sales[Revenue])

Total Profit = SUM(Sales[Profit])

Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

Year-over-Year Growth = ([Current Year Sales] - [Previous Year Sales]) / [Previous Year Sales]

Dashboard Design and Visualization
A well-designed dashboard should be visually appealing and easy to interpret. The Adidas sales analysis dashboard includes:

Sales Overview

Total revenue, total profit, and total sales volume (KPIs).

Comparison of monthly sales trends using a line chart.

Year-over-Year (YoY) growth analysis with percentage change indicators.

Product Performance

A bar chart showing the best-selling Adidas product categories.

Revenue contribution by product type (shoes, apparel, accessories).

A matrix table displaying product-wise sales details.

Geographical Analysis

An interactive map visualizing sales performance across different regions.

Country-wise revenue contribution using a choropleth map.

Drill-through functionality to analyze sales at the state/city level.

Customer Insights

A donut chart representing customer segmentation (age group, gender).

Customer lifetime value and average order value metrics.

Repeat customers vs. new customers comparison.

Time-Based Analysis

Monthly and quarterly sales trends using a stacked column chart.

Seasonality patterns to identify peak sales periods (e.g., holiday seasons).

Interactivity and Filters
Power BI enables users to interact with the dashboard using:

Slicers to filter data by product category, region, or customer segment.

Drill-through features for detailed analysis (e.g., clicking a region on the map to see state-wise sales).

Bookmarks and tooltips for better data storytelling.

Insights and Business Impact
The Adidas Sales Analysis 2021 dashboard provides valuable insights, such as:

Identifying the most profitable product categories.

Recognizing underperforming regions to improve marketing strategies.

Understanding customer purchasing behavior to enhance personalization.

Forecasting future sales based on historical trends.

Conclusion
Building a Power BI dashboard for Adidas’ 2021 sales analysis involves data collection, transformation, modeling, visualization, and interactivity. By leveraging Power BI’s capabilities, Adidas can gain actionable insights to drive revenue growth, optimize marketing efforts, and improve overall business performance.









