# Inventory & Supply Chain Analysis

## Project Overview
This project analyzes inventory, sales, and purchasing data to evaluate inventory performance, identify stock risks, assess product sales performance, and analyze supplier purchasing costs.

The goal is to turn raw operational data into actionable business insights that can support better inventory management and purchasing decisions.

## Business Objectives
- Evaluate inventory value and stock availability.
- Identify stockout products and potential lost sales.
- Detect slow-moving and low-stock products.
- Analyze sales performance by product and category.
- Evaluate supplier purchasing costs and Purchase Price Variance (PPV).
- Analyze supplier delivery delays.

## Dataset Description
The project uses three related datasets:

- **Items & Stock:** 3,600 records
- **Sales:** 3,434 records
- **Purchases:** 2,461 records

The datasets contain information about 150 products across different categories, suppliers, and monthly periods.

**Data Source:** [Inventory Data Studio](https://inventoryoptimization.pro/inventory-data-studio/)

*Note: The datasets are synthetic training data.*

## Data Cleaning & Preparation
Data preparation was performed using Excel Power Query.

Key steps included:
- Reviewing data types and missing values.
- Checking duplicate records and key combinations.
- Validating numeric fields and identifying unusual values.
- Creating a Delivery Delay column.
- Creating a PPV Status classification.
- Preparing a separate inventory snapshot for August 2026.
- Retaining missing values where no reliable replacement was justified.

## Analysis & Key Findings

### 1. Inventory Analysis
- Total Inventory Value: **1,808,349.87**
- Available Stock Units: **75,245**
- Stockout Products: **3**
- Low Stock Coverage Products (less than 2 weeks): **9**
- Slow-Moving Products (more than 90 days): **8**
- Slow-moving inventory represents approximately **17.09%** of total inventory value.

### 2. Sales Analysis
- Total Units Sold: **827,790**
- Total Products Analyzed: **150**
- Highest Revenue Category: **Fluid Power**
- Electrical recorded the highest sales volume by units.
- Identified the top and bottom 5 products by revenue and units sold.

### 3. Purchasing & Supplier Analysis
- Total Purchase Value: **17,425,237.81**
- Total Quantity Received: **833,807**
- Net Purchase Price Variance: **259,122.31**
- Granite Partners recorded the highest positive PPV.
- Summit Trading was the only supplier with a negative net PPV.

## Dashboards
The project includes three interactive Excel dashboards:

1. **Inventory Dashboard:** Inventory value, stock health, stock coverage, slow-moving products, and low-stock products.
2. **Sales Dashboard:** Revenue and units sold by category, top-performing products, and lowest-performing products.
3. **Purchases Dashboard:** Purchase value, supplier performance, PPV, quantities received, unit costs, and delivery delays.

## Tools & Skills
- Microsoft Excel
- Power Query
- PivotTables
- PivotCharts
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Inventory Analysis
- Sales Analysis
- Supplier Performance Analysis
- Data Visualization

## Conclusion
This project demonstrates how Excel can be used to transform multiple operational datasets into structured analysis and interactive dashboards.

The findings highlight inventory risks, sales performance differences, and supplier cost variations that can help businesses make more informed operational decisions.

## Dashboard Screenshots

### Inventory Dashboard
![Inventory Dashboard](image/inventory-dashboard.png)

### Sales Dashboard
![Sales Dashboard](image/sales-dashboard.png)

### Purchases Dashboard
![Purchases Dashboard](image/purchases-dashboard.png)
