# Lab 3 - Exploratory Data Analysis (EDA)
**ARTI 308 - Machine Learning**

## Dataset
- **Name**: Chocolate Sales Dataset  
- **Description**: Sales records of various chocolate products across multiple countries from 2022 to 2024.  
- **File**: `Chocolate_Sales.csv`  
- **Rows**: 1,000+ records  
- **Columns**: Sales Person, Country, Product, Date, Amount, Boxes Shipped

## Problem Definition
This lab performs Exploratory Data Analysis (EDA) on the Chocolate Sales dataset to:
- Understand monthly revenue trends
- Identify the best-selling countries and products
- Analyze the relationship between boxes shipped and revenue
- Extract useful business insights from the sales data

## Methodology
- Loaded the dataset using Pandas
- Cleaned the `Amount` column (removed $ sign and commas)
- Converted `Date` column to datetime and extracted monthly periods
- Created visualizations using Matplotlib and Seaborn:
  - Monthly Revenue Trend
  - Total Sales by Country
  - Top 10 Products by Revenue
  - Relationship between Boxes Shipped and Amount
- Summarized key insights

## Key Insights
- The highest revenue is generated in the top-performing country
- The most popular product by revenue is the highest-selling chocolate product
- Total revenue across all sales shows strong overall performance
- There is a strong positive relationship between the number of boxes shipped and revenue
[chocolate_sales_eda.ipynb](chocolate_sales_eda.ipynb)

---

**Submitted by:** Zainab Malik  
**Date:** April 2026
