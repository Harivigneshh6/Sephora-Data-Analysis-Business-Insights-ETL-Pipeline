# Sephora Data Analysis: Business Insights & ETL Implementation

## 📌 Project Overview
This project analyzes Sephora’s product and customer review dataset to extract actionable business insights. It involves data cleaning, ETL processing, OLAP cube modeling, SQL-based analysis, and Power BI visualization.

## 🎯 Objectives
- **Data Cleaning**: Handled missing values, duplicates, and inconsistencies using SSMS and Alteryx.
- **ETL Processing**: Extracted, transformed, and loaded data using Alteryx.
- **Data Analysis**: SQL-based analysis to explore customer sentiment, product trends, and sales impact.
- **OLAP Cube Modeling**: Enabled multidimensional data analysis.
- **Visualization**: Developed Power BI dashboards for business insights.

## 🔍 Data Sources
- **Product Data**: 8,000+ beauty products with pricing, availability, and customer engagement metrics.
- **Review Data**: 1M+ user reviews including ratings, sentiment, and feedback.

## 🛠️ Technologies Used
- **SQL Server Management Studio (SSMS)**
- **Alteryx** (ETL processing)
- **Power BI** (Data visualization)
- **Python** (Pandas, PySpark)
- **OLAP Cube** (Multidimensional analysis)

## 📊 Key Insights
- **Top-Rated Products**: Face Gym’s Vitamin C Oil Serum had the highest rating.
- **Most Recommended**: Laneige’s Lip Sleeping Mask.
- **Price vs. Ratings**: Luxury products had higher ratings than budget products.
- **Stock Availability**: Sephora Collection Cleansing Wipes were frequently out of stock.
- **Customer Sentiment**: 72.95% satisfaction rate, surpassing the benchmark goal.
  
## 🚀 How to Run
1. Load the dataset into **SQL Server**.
2. Use 'Fact and Dimension Creation.sql' to create facts and dimensions tables for the OLAP Cube.
3. Execute 'FinalSephora' **Alteryx Workflow** to transform and load data.
4. Use `pysprk_insight.py` for analysis and reporting.
5. Open `sephora dashboard.pbix` to explore the visualized insights.

## 📜 Conclusion
This analysis provides key insights into Sephora’s business trends, customer preferences, and inventory challenges. The findings help in **stock optimization, customer sentiment tracking, and data-driven decision-making**.
