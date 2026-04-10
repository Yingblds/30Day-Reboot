# E-commerce Sales Analysis

## Project Overview

This project analyzes e-commerce sales data to uncover insights into sales performance, product trends, and customer purchasing behavior. The goal is to transform raw transactional data into actionable business insights.

## Business Context

E-commerce platforms generate large volumes of transactional data daily. Understanding this data is crucial for:
- Optimizing product offerings
- Improving marketing strategies
- Enhancing customer experience
- Increasing overall revenue
This project simulates a real-world business scenario where data analysis supports decision-making.

## Objectives

- Analyze overall sales performance over time
- Identify top-performing and underperforming products
- Explore customer purchasing patterns
- Discover trends across categories, regions, or time
- Generate actionable business insights

## Data Description

- Source:
The dataset used in this project is the Online Retail II dataset, publicly available on platforms such as Kaggle and the UCI Machine Learning Repository.
It contains transactional data for a UK-based online retail store.
This dataset is widely used for customer segmentation, cohort analysis, and retail analytics tasks.
- Format: CSV
- Key Features:
  · Invoice
  · StockCode
  · Description
  · Quantity
  · InvoiceDate
  · Price
  · Customer ID
  · Country
- Size:
  · Number of rows: 
  Before cleaning: 541,910 rows
  After cleaning (removing missing Customer IDs and returns): 531,286 rows
  · Time range:
  The dataset covers transactions from December 1, 2010 to December 9, 2011

## Data Cleaning

· Removed missing Customer IDs
· Filtered out negative quantities (returns)
· Create TotalPrice = Quantity * Price
· Converted date fields to proper datetime format

## Analysis Performed

1. Sales Trend Analysis
· Monthly aggregation of total revenue
· Identified overall growth pattern and seasonality
2. Moving Average
· Applied 3-month rolling average
· Smoothed fluctuations to reveal underlying trends
3. Growth Rate Analysis
· Calculated month-over-month growth
· Identified volatility and peak performance periods
4. Top Customers & Countries
· Ranked top-performing customers and regions
· Observed strong revenue concentration
5. RFM Alalysis (Customer Segmentation)
· Recency: Days since last purchase
· Frequency: Number of purchases
· Monetary: Total spending
· Segmented customers into behavioral groups
6. Cohort Analysis (Customer Retention)
· Grouped customers by first purchase month
· Calculated retention rates over time
· Visualized retention patterns using heatmap

## Notebook

- ecommerce_analysis_pracitce.ipynb
  ・ Step-by-step exploration
  ・ Intermediate analysis and experimentation
- ecommerce_analysis_final.ipynb
  ・ Clean and structured
  ・ Ready for presentation

## Key Insights

· Sales show an overall upward trend but with significant volatility
· Growth is inconsistent and likely influenced by seasonal or promotional factors
· A small segment of customers contributes a large portion of revenue (Pareto effect)
· Customer retention drops sharply after the first purchase
· Long-term engagement is driven by a relatively small group of loyal customers

## Business Recommendations

· Improve early-stage customer retention (first-month experience)
· Identify and replicate drivers behind peak sales periods
· Focus on retaining high-value customers
· Develop targeted re-engagement strategies for ar-risk users

## Tool

- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

## Future Improvements

- Add predictive modeling (e.g., churn prediction)
- Perform time series forecasting
- Incorporate customer lifetime value (CLV) analysis
- Build interactive dashboard (Tableau/Power BI)

## Author

Github: https://github.com/Yingblds