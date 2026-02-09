# Inventory & Sales Data Analysis

## Project Overview
This project analyzes retail sales and inventory data to evaluate revenue performance,
inventory efficiency, and short-term demand behavior. The goal is to extract
operational insights that support business decision-making rather than build
complex predictive models.

Due to the limited historical time span of the available data (January–February 2016),
the analysis focuses on descriptive and diagnostic analytics instead of long-term
forecasting.

---

## Business Objectives
- Analyze month-over-month sales performance
- Evaluate changes in revenue and units sold
- Assess inventory turnover and stock efficiency
- Identify dead stock, slow-moving, healthy, and fast-moving inventory
- Demonstrate demand comparison under real-world data constraints

---

## Datasets Used
The analysis uses multiple structured CSV datasets, including:
- Sales transaction data
- Purchase records
- Beginning and ending inventory snapshots
- Invoice-level purchase details
- Product pricing information

> Note: Due to GitHub file size limits, large CSV files are not included in this repository.

---

## Analysis Workflow

### 1. Data Preparation
- Data cleaning and validation
- Date standardization
- Monthly aggregation of sales data

### 2. Sales Performance Analysis
- Month-over-month revenue comparison
- Month-over-month units sold comparison
- Visualizations designed to avoid misleading trend interpretation

### 3. Key Performance Indicators (KPIs)
- Percentage change in total revenue
- Percentage change in total units sold

These KPIs provide a concise business-level summary of performance shifts.

### 4. Inventory Analysis
- Inventory turnover calculation
- Distribution analysis of turnover values
- Inventory segmentation into:
  - Dead Stock
  - Slow Moving
  - Healthy
  - Fast Moving

This segmentation supports inventory planning and working capital decisions.

### 5. Demand Comparison (Data-Constrained Analysis)
- Month-over-month demand comparison using discrete observations
- No long-term forecasting applied due to insufficient historical data

---

## Key Insights
- Revenue and units sold declined significantly from January to February 2016
- A substantial portion of inventory shows low or zero turnover, indicating overstock risk
- Fast-moving products require careful replenishment despite demand volatility
- Inventory strategy should prioritize reducing dead stock and protecting high-velocity items

---

## Limitations
- Short historical time span limits trend and seasonality analysis
- No pricing elasticity or customer segmentation included
- Results should be interpreted as operational insights, not predictive outcomes

---

## Future Enhancements
- Multi-period demand forecasting with extended historical data
- SKU-level inventory optimization models
- Integration of pricing, promotions, and lead-time effects
- Advanced supply-chain performance metrics

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib
- Google Colab / Jupyter Notebook

---

## Author
Tejas  
Data Analyst Intern  
Unified Mentor

