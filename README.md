# Walmart Store Sales Analysis & Forecasting

## Project Overview

This project focuses on analyzing Walmart's weekly sales data to identify sales trends, evaluate store performance, understand the impact of holidays, and develop machine learning models to predict weekly sales.

This project was completed as a **Course-End Project** as part of the Applied Data Science learning process, applying Python programming, exploratory data analysis, data visualization, and machine learning techniques to a retail sales dataset.

## Project Objectives

- Identify the store with the highest total sales.
- Analyze sales variations across stores using Standard Deviation and Coefficient of Variation.
- Compare Q2 and Q3 sales growth for 2012.
- Examine the impact of holidays on weekly sales.
- Analyze monthly and semester-wise sales trends.
- Investigate relationships between sales and economic factors such as CPI, unemployment, and fuel prices.
- Develop a weekly sales prediction model for Store 1.
- Compare machine learning models and evaluate their performance.

## Technologies & Libraries Used

- **Python** – Programming and analysis
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computing
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Scikit-learn** – Machine learning and model evaluation
- **Jupyter Notebook** – Interactive development environment

## Dataset Description

The dataset contains **6,435 records and 8 columns**.

| Column | Description |
|---|---|
| Store | Store identification number |
| Date | Weekly sales date |
| Weekly_Sales | Sales recorded for the week |
| Holiday_Flag | Indicates whether the week includes a holiday |
| Temperature | Temperature during the week |
| Fuel_Price | Fuel price during the week |
| CPI | Consumer Price Index |
| Unemployment | Unemployment rate |

## Project Workflow

### 1. Data Loading & Inspection
- Imported the dataset using Pandas.
- Examined dataset dimensions, data types, and structure.
- Checked for missing values and duplicate records.

### 2. Exploratory Data Analysis
- Performed store-wise sales analysis.
- Identified stores with the highest sales and sales variability.
- Analyzed quarterly sales growth.
- Investigated holiday and non-holiday sales.
- Generated monthly and semester-wise sales summaries.

### 3. Data Visualization
- Created charts to compare store performance.
- Visualized sales trends and seasonal patterns.
- Examined relationships between sales and economic indicators.

### 4. Machine Learning & Forecasting
- Selected Store 1 data for sales prediction.
- Converted dates into numerical day values.
- Prepared features for model training.
- Implemented Linear Regression and Random Forest Regression.
- Evaluated models using MAE, RMSE, and R².
- Compared model performance to identify the better-performing model.

## Key Learnings

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Statistical Analysis
- Data Visualization
- Feature Engineering
- Correlation Analysis
- Regression Analysis
- Machine Learning Model Training
- Model Evaluation and Comparison
- Sales Forecasting

## Conclusion

This project demonstrates the practical application of data science techniques in retail analytics. Through exploratory analysis, statistical methods, visualization, and machine learning, the project provides insights into Walmart's store sales performance and explores predictive modeling for future sales estimation.

## Future Improvements

- Perform hyperparameter tuning to improve model performance.
- Explore advanced time-series forecasting techniques.
- Introduce additional sales-related features.
- Develop an interactive dashboard for better business insights.

---

**Project Type:** Course-End Project  
**Domain:** Applied Data Science | Retail Analytics | Machine Learning
