# 🛒 PySpark Sales Analytics Project

This project showcases a comprehensive retail sales analytics pipeline built using **PySpark in Databricks**. It demonstrates how to ingest, transform, and analyze transactional data to uncover insights about customer behavior, product performance, and sales trends across time and geography.

---

## 📁 Project Overview

The goal of this project is to:
- Analyze customer spending patterns
- Identify top-performing products
- Track monthly and yearly sales trends
- Compare sales across countries and order sources
- Create pivot-style summaries for customer engagement

The project uses two CSV datasets:
- **Sales Data**: Contains transaction-level details
- **Menu Data**: Contains product metadata and pricing

---

## 🚀 Technologies Used

- Apache Spark (PySpark)
- Databricks Notebook
- Spark SQL Functions
- CSV File Format
- DataFrames and Aggregations

---

## 📦 Data Sources

### 1. Sales Dataset
Includes fields such as:
- Product ID
- Customer ID
- Order Date
- Location (Country)
- Source of Order (e.g., App, Website)

### 2. Menu Dataset
Includes:
- Product ID
- Product Name
- Price

---

## 🔧 Data Preparation

- Defined custom schemas for both datasets to ensure consistent data types.
- Enriched the sales data by extracting **year**, **month**, and **quarter** from the order date.
- Joined the sales and menu datasets using `product_id` to enable price-based analysis.

---

## 📊 Key Analyses

### Customer Spend Analysis
Calculated total amount spent by each customer across all transactions.

### Product Performance
Aggregated total revenue and number of orders for each product to identify bestsellers.

### Time-Based Sales Trends
Analyzed total sales by:
- Month
- Year
- Quarter

### Geographic and Source-Based Insights
Grouped sales by:
- Country (location)
- Order source (e.g., app, website)

### Customer Engagement Pivot
Created a pivot-style summary showing number of orders per customer across different order sources.

---

## 📈 Insights Uncovered

- Top-spending customers and most frequently ordered products
- Seasonal trends in sales volume and revenue
- Regional performance differences across countries
- Order source preferences and customer distribution

---

## 🧠 Future Enhancements

- Add product categories for deeper segmentation
- Integrate real-time streaming for live dashboards
- Export results to BI tools like Power BI or Tableau
- Apply machine learning for demand forecasting or anomaly detection

---

## 🗂️ How to Use

1. Upload the CSV files to your Databricks workspace.
2. Open the notebook and run each cell sequentially.
3. Use `display()` to visualize tables and charts interactively.
4. Modify filters and groupings to explore additional insights.

---

## 📬 Contact

For questions, feedback, or collaboration opportunities, feel free to reach out via GitHub or LinkedIn.

---
