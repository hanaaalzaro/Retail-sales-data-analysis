# Retail Sales Data Analysis

## Overview
This project performs an end-to-end **data science analysis** on a retail sales dataset.  
The goal is to uncover business insights such as revenue drivers, seasonal trends, customer demographics, and high-value customers using Python.

## Tools & Libraries
- **Python (pandas, numpy)** → data cleaning & feature engineering  
- **Matplotlib / Seaborn** → visualizations  
- **Jupyter Notebook** → interactive analysis & reporting  

## Dataset
The dataset contains 500+ retail transactions with the following fields:
- `Transaction ID`  
- `Date`  
- `Customer ID`  
- `Gender`  
- `Age`  
- `Product Category`  
- `Quantity`  
- `Price per Unit`  
- `Total Amount`  

## Data Preparation
- Converted `Date` into datetime and extracted **Month, Day, Year, Quarter**.  
- Created **Age Groups** (18–29, 30–39, 40–49, 50–59, 60–69).  
- Engineered **Revenue** feature (`Quantity × Price per Unit`) and validated against `Total Amount`.  
- Checked for missing values and anomalies.  

## Exploratory Data Analysis (EDA)
- **Revenue by Category** → Electronics generated the highest revenue.  
- **Seasonal Trends** → Strong peaks in November–December, mid-year dips.  
- **Customer Demographics** →  
  - Female customers spent slightly more on average.  
  - 30–39 age group was the most active buyers.  
- **Top Customers** → A small group of high-value customers contributed disproportionately to revenue.  
- **Correlation Analysis** → Revenue strongly correlated with price and quantity, weak correlation with age.

## Insights & Recommendations
- Stock more **electronics** before the holiday season.  
- Target promotions to the **30–39 age group**.  
- Develop loyalty programs for **high-value customers**.  
- Balance seasonal dips with mid-year campaigns.  

