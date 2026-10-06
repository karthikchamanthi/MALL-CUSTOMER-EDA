# MALL-CUSTOMER-EDA
**Mall Customers — Clean, Explore &amp; Engineer**  A data analysis project focused on cleaning the Mall Customers dataset, performing exploratory data analysis (EDA), identifying customer patterns, and engineering new features such as age groups, income groups, and income-per-age for future machine learning and customer segmentation.
# Mall Customers — Clean, Explore & Engineer

## Project Overview

This project focuses on cleaning, exploring, and preparing the Mall Customers dataset for potential machine learning applications. The analysis covers data quality checks, exploratory data analysis (EDA), and feature engineering to better understand customer demographics, income, and spending behavior.

## Data Cleaning

The dataset was first examined for missing values, duplicate records, and potential outliers. Missing values were identified using `isnull()` and handled using appropriate imputation methods. Duplicate records were identified and removed to maintain data quality. Potential numerical outliers were detected using the Interquartile Range (IQR) method and handled through value capping to reduce their influence without unnecessarily removing customer records.

## Exploratory Data Analysis

Several visualizations were created to understand patterns within the data.

- **Age Distribution:** Examines the distribution of customer ages and identifies the most common age ranges.
- **Annual Income Distribution:** Shows the spread of customer income levels and helps identify typical income ranges and extreme values.
- **Age vs. Annual Income:** Uses a scatter plot to explore the relationship between customer age and annual income, with gender used for group comparison.
- **Correlation Heatmap:** Displays relationships between numerical variables and helps identify potentially useful features for future modeling.
- **Spending Score by Gender:** Compares spending behavior between genders using a box plot.
- **Spending Score by Age Group:** Compares spending behavior across Young, Mid, and Old customer segments.

## Feature Engineering

Three new features were created to improve the dataset for future modeling:

1. **Age_Group** — Categorizes customers into Young, Mid, and Old groups.
2. **Income_Group** — Categorizes customers into Low, Medium, and High income groups.
3. **Income_per_Age** — Represents annual income relative to customer age.

## Key Insights

The analysis provides an overview of customer demographics, income distribution, and spending behavior. Customer characteristics vary across age and income levels, while spending scores show differences across customer segments. Correlation analysis helps identify relationships between numerical variables, and age-based segmentation provides an additional perspective on customer spending behavior. These findings can support future customer segmentation and predictive modeling.
