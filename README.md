
📦 Inventory & Sales Data Analysis (Data Analyst Project)
📌 Project Overview

This project analyzes retail sales and inventory data to assess revenue performance, inventory efficiency, and short-term demand behavior.

The objective is to extract operational insights that support business decision-making, such as identifying demand changes, inventory risks, and stock movement patterns.

Due to the limited historical time span (January–February 2016), the analysis focuses on descriptive and diagnostic analytics rather than long-term forecasting.

🎯 Business Objectives

Analyze month-over-month sales performance

Evaluate units sold and revenue changes

Assess inventory turnover and stock efficiency

Identify dead stock, slow-moving, and fast-moving inventory

Demonstrate baseline demand comparison under data constraints

📂 Datasets Used

The project uses multiple structured CSV datasets, including:

Sales transactions

Purchase records

Beginning and ending inventory

Invoice-level purchase details

Product pricing information

Note: Large CSV files are not uploaded to this repository due to GitHub size limits.

🧠 Analysis Approach
1. Data Preparation

Data cleaning and type correction

Date standardization

Monthly aggregation of sales data

2. Sales Performance Analysis

Month-over-month revenue comparison

Month-over-month units sold comparison

Clear visualization without overstating trends

3. Key Performance Indicators (KPIs)

Percentage change in revenue

Percentage change in units sold
These KPIs provide a concise business-level view of performance shifts.

4. Inventory Analysis

Inventory turnover calculation

Distribution analysis of turnover values

Segmentation of inventory into:

Dead Stock

Slow Moving

Healthy

Fast Moving

This segmentation supports inventory planning and working capital decisions.

5. Demand Comparison (Data-Constrained)

Month-over-month demand comparison using discrete observations

No long-term forecasting applied due to insufficient historical depth

📊 Key Insights

Significant decline in revenue and units sold from January to February 2016

A meaningful portion of inventory shows low or zero turnover, indicating potential overstock risk

Fast-moving products require careful replenishment despite demand volatility

Inventory optimization should prioritize reducing dead stock and protecting high-velocity items

⚠️ Limitations

Analysis limited to a short historical period

No seasonality or long-term trend inference

No pricing elasticity or customer segmentation analysis

🚀 Future Enhancements

Multi-period demand forecasting with extended historical data

SKU-level predictive inventory optimization

Integration of pricing and promotion effects

Advanced supply-chain metrics (lead time, service level)

🛠️ Tools & Technologies

Python

Pandas, NumPy

Matplotlib

Google Colab / Jupyter Notebook
