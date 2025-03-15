# oibis_task01
exploratory data analysis
# Exploratory Data Analysis (EDA)

##  Project Overview

This project analyzes retail sales data to uncover insights into customer behavior, sales trends, and product performance.

Using Python, we perform data cleaning, exploratory data analysis (EDA), and time-series analysis to understand key sales drivers.

## Dataset

The dataset consists of 1,000 transactions with 9 columns:
- Date – Transaction date
- Age – Customer’s age
- Gender – Male/Female
- Product Category – Clothing, Electronics, Beauty
- Quantity – Items purchased
- Price per Unit – Cost per item
- Total Amount – Total spent per transaction.

# Analysis
## 1.Data Cleaning & Preprocessing
- Handled missing values and duplicates
- Converted the Date column to datetime format
- Performed descriptive statistics for numerical and categorical features
## 2. Descriptive Statistics & Insights
- Average customer age: 41 years
- Average transaction value: $456
- Most common purchase: 4 items at $50 each
- Majority buyers: Female customers, mostly purchasing clothing
  
## 3. Time-Series Analysis
- **Sales Trend Over Time:**

Spikes in sales due to seasonal trends & promotions. Highest sales in June 2023; lowest in October 2023

Overall quarterly growth in 2023, slight dip in early 2024. 

## 4. Customer & Product Analysis
- Genders : 51% Female, 49% Male
- Total revenue: ~$456,000 (Females: $232,840, Males: $223,160)
- **Category Preferences:**
- Females: Clothing & Beauty
- Males: Electronics
  
## 4. Visualizations
This project includes various data visualizations using Matplotlib & Seaborn:
-  Sales trends over time (Daily, Monthly, Quarterly)
-  Donut chart for total spending by gender
-  Bar charts for spending by category & gender
-  Histogram for customer age distribution
-  Boxplots for gender vs. spending behavior

##  Tech Stack

Python (Pandas, Seaborn, Matplotlib)

Jupyter Notebook

Git/GitHub for version control
