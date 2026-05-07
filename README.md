# E-Commerce Sales Analysis Dashboard

---

# Objective

This project focuses on analyzing e-commerce sales data using Microsoft Excel to identify business insights, sales trends, and customer purchasing patterns.

The main objectives of this project are:

- Analyze sales performance across regions and categories
- Identify top-performing products and brands
- Understand customer purchasing behavior
- Evaluate payment method performance
- Create an interactive sales dashboard for business reporting

---

# Dataset Information

- Source: E-Commerce Sales Dataset
- Tool Used: Microsoft Excel
- Tables: 4
- Rows: 2000+
- Data Model: Star Schema

## Tables Included

- Customer_Dim
- Product_Dim
- Store_Dim
- Sales_Fact

---

# Data Cleaning and Preparation

The following preprocessing steps were performed:

- Removed duplicate records
- Handled missing values using mean and median methods
- Standardized text values using TRIM and PROPER functions
- Corrected inconsistent Product_ID formats
- Validated row and column counts
- Created Loyalty_Level column using IF conditions
- Converted raw data into structured Excel tables

---

# Excel Functions and Features Used

## Functions Used

- IF
- XLOOKUP
- SUM
- AVERAGE
- COUNTIF
- TEXT
- TRIM
- PROPER

## Excel Features Used

- Pivot Tables
- Pivot Charts
- Sparklines
- Data Analysis ToolPak
- Slicers
- Relationship Modeling

---

# Data Modeling

Relationships were created between dimension tables and the Sales_Fact table using primary and foreign keys.

An active relationship model was maintained to ensure accurate filtering and reporting across the dashboard.

---

# Dashboard and Visualization

An interactive dashboard was created using Pivot Charts and slicers.

## Dashboard Insights

- Total Sales
- Average Sales
- Total Orders
- Payment Type Analysis
- Region-wise Sales
- Category-wise Sales
- Monthly Sales Trends
- Top Performing Brands

## Slicers Added

- Category
- Region
- Payment Type
- Order Month

---

# Key Insights

- Identified top-performing product categories and brands
- Analyzed monthly and regional sales trends
- Evaluated payment method performance
- Improved reporting accuracy through data cleaning and transformation

---

# Conclusion

This project demonstrates the effective use of Microsoft Excel for data cleaning, analysis, visualization, and dashboard creation.

The final dashboard provides meaningful business insights that support data-driven decision-making and performance analysis.
