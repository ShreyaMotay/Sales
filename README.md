# Retail Sales Analytics Dashboard

## Overview

This project analyzes retail sales data using Python (Pandas) and Power BI to uncover trends in revenue, profit, product performance, and regional sales. The objective was to clean and transform raw sales data, generate business insights, and create an interactive dashboard for decision-making.

---

## Project Objectives

- Clean and preprocess retail sales data
- Analyze sales and profit performance
- Identify top-performing products and categories
- Analyze regional sales trends
- Create an interactive Power BI dashboard
- Generate actionable business insights

---

## Tools & Technologies

- Python
- Pandas
- Jupyter Notebook
- Power BI
- CSV Data Files

---

## Dataset

The dataset contains retail transaction records including:

- Order Information
- Product Categories
- Sales
- Profit
- Quantity
- Customer Segments
- Regions and States

---

## Data Cleaning Process

The following steps were performed using Python:

- Removed duplicate records
- Handled missing values
- Standardized data formatting
- Exported cleaned dataset for reporting

Example:

```python
import pandas as pd

df = pd.read_csv("Sales.csv", encoding="latin1")

df = df.drop_duplicates()
df = df.dropna()

df.to_csv("Cleaned_Sales.csv", index=False)
```

---

## Dashboard Features

### KPI Cards

- Total Sales: $2.30M
- Total Profit: $286K
- Total Quantity Sold: 38K
- Average Order Value: $541

### Visualizations

- Monthly Sales Trend
- Sales by Product Category
- Sales by Region
- State-wise Sales Map
- Top Selling Products

---

## Key Insights

- Technology was the highest-performing category.
- The West region generated the highest revenue.
- Sales peaked during November and December.
- Phones and Chairs were the top-selling products.
- Total profit exceeded $286K.

---

## Business Recommendations

- Increase inventory for top-performing products.
- Focus marketing efforts on high-revenue regions.
- Prepare inventory and promotions ahead of Q4 demand spikes.
- Continue investing in Technology-related product categories.

## Skills Demonstrated

- Data Cleaning
- Data Analysis
- Exploratory Data Analysis (EDA)
- Data Visualization
- KPI Reporting
- Business Intelligence
- Power BI Dashboard Development
- Python (Pandas)


