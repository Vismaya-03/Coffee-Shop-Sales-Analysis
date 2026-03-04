# Coffee Shop Sales Analysis & Dashboard

## Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a coffee shop sales dataset to uncover key business insights related to **revenue trends, customer purchasing patterns, product performance, and store location performance**.

The analysis was performed using **Python**, and the insights were visualized through an **interactive Power BI dashboard**.

The goal of the project is to demonstrate **data cleaning, feature engineering, exploratory analysis, and business intelligence visualization** skills commonly used by data analysts.


# Business Objectives

The analysis focuses on answering the following questions:

- Which **product categories generate the highest revenue**?
- Which **store location performs the best**?
- At what **time of day are sales highest**?
- Which **products contribute most to revenue**?
- How do **sales trends vary by month and day of week**?


# Dataset Information

The dataset contains transactional data from multiple coffee shop locations.

### Key Columns

| Column | Description |
|------|------|
| transaction_id | Unique transaction identifier |
| transaction_date | Date of purchase |
| transaction_time | Time of purchase |
| store_location | Coffee shop branch location |
| product_category | Category of the product |
| product_type | Type of product |
| product_detail | Detailed product name |
| transaction_qty | Number of items purchased |
| unit_price | Price per item |


# Tools & Technologies

### Programming & Analysis
- Python
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn

### Business Intelligence
- Power BI

### Environment
- Jupyter Notebook

---

# Data Processing Steps

The following steps were performed during analysis.

## Data Understanding
- Dataset inspection
- Checking structure and datatypes
- Summary statistics

## Data Cleaning
- Handling missing values
- Correcting data types
- Removing unnecessary columns

## Feature Engineering

New features were created to enhance analysis:

- transaction_year
- transaction_month
- transaction_day
- time_of_day (Morning / Afternoon / Evening)
- product_size
- total_amount

Example:

```python
shop_analysis['total_amount'] = shop_analysis['transaction_qty'] * shop_analysis['unit_price']
```

# Exploratory Data Analysis

## Univariate Analysis
Understanding individual variables:

- Distribution of product prices
- Product category frequency
- Transaction quantity distribution
- Outlier detection using boxplots

## Bivariate Analysis
Studying relationships between variables:

- Revenue by product category
- Revenue by store location
- Quantity vs revenue
- Sales trends by time of day

## Multivariate Analysis

- Correlation heatmap
- Sales trends across multiple variables


# Power BI Dashboard

An interactive dashboard was created to visualize key insights.

### Dashboard Features

- Revenue by Month
- Revenue by Time of Day
- Top Product Categories
- Product Size Distribution
- Revenue by Store Location
- Sales by Day of Week

### Dashboard Filters

- Month
- Store Location
- Product Category

The dashboard enables quick exploration of sales patterns across different dimensions.


# Key Insights

###  Beverages Drive Most Revenue
Beverages contribute the highest share of revenue across all store locations, making them the primary revenue driver.

### Store Performance Varies
Certain locations generate significantly higher revenue, indicating differences in customer traffic and demand.

### Peak Sales During Specific Hours
Most transactions occur during peak coffee hours, particularly in the mornings.

### Complementary Products Matter
Bakery items and snacks contribute additional revenue alongside beverage purchases especially in the morning.

### Most Orders Contain Few Items
The majority of transactions involve purchasing a small number of items.

# Business Recommendations

Based on the analysis:

- Promote high-performing beverage categories
- Offer bundle deals (coffee + bakery items)
- Optimize staffing during peak sales hours
- Replicate successful product mixes across locations


# Skills Demonstrated

This project demonstrates:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Business Insight Generation
- Data Visualization
- Dashboard Design
- Business Intelligence Reporting

# Future Improvements

Possible improvements include:

- Sales forecasting models
- Customer segmentation analysis
- Profit margin analysis
- Automated dashboard updates

