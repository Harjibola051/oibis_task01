# oibis_task01
exploratory data analysis
# Exploratory Data Analysis (EDA)

## Overview
This project performs exploratory data analysis (EDA) on a retail sales dataset to uncover patterns, trends, and insights from the data.

## Objectives
- Data cleaning and transformation
- Descriptive statistics and data visualization
- Time series analysis

## Dataset
- Source: retail_sales_dataset.csv
- Description: Contains sales data with 9 columns and 1000 entries
- Key features: Quantity, Price per Unit, Total Amount, Gender, Product Category, and Date
  

## Key Analysis Steps

### 1. Data Loading and Cleaning
- No null values detected
- Date column converted to datetime format
- Duplicate rows removed

### 2. Descriptive Statistics
- Numerical columns' mode values:
  - Quantity: 4
  - Price per Unit: $50
  - Total Amount: $50
- Categorical columns' mode values:
  - Gender: Female
  - Product Category: Clothing

### 3. Time Series Analysis
- Aggregate sales over time
- Quarterly sales trend
- Monthly sales trend

## Results
- Most purchases involved 4 items with each unit priced at $50
- Female customers are more active, and Clothing is the most sought-after product category
- Sales trends show seasonal fluctuations

## Tools and Libraries
- Python 3.x
- Pandas
- Seaborn
- Matplotlib



