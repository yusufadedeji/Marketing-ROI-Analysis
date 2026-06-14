# Marketing ROI Analysis Using Simple Linear Regression

## Project Overview

This project analyzes the relationship between marketing channels and sales performance using exploratory data analysis and simple linear regression.

The goal is to identify the marketing channel with the strongest impact on sales, build a statistically valid regression model, evaluate model performance, and provide a data-driven recommendation for marketing budget allocation.

## Objectives

- Load and clean marketing dataset
- Perform exploratory data analysis (EDA) using visualizations
- Identify the marketing channel most correlated with sales
- Build an Ordinary Least Squares (OLS) regression model using `statsmodels`
- Evaluate regression assumptions through diagnostic plots
- Interpret model results in a business context
- Provide ROI-based marketing recommendations

## Dataset

The dataset contains marketing expenditure across different channels:

- TV Advertising
- Radio Advertising
- Social Media Advertising
- Sales Performance

Missing values were identified and handled before analysis.

## Analysis Workflow

1. Data loading and preprocessing
2. Exploratory Data Analysis:
   - Distribution analysis
   - Correlation analysis
   - Relationship visualization between marketing channels and sales
3. Variable selection based on correlation strength
4. Simple Linear Regression modeling:
   - Independent variable: TV advertising spend
   - Dependent variable: Sales
5. Model evaluation using:
   - R-squared
   - Regression coefficients
   - p-values
6. Regression diagnostics:
   - Linearity
   - Normality of residuals
   - Homoscedasticity

## Key Findings

- TV advertising showed the strongest relationship with sales compared with Radio and Social Media.
- The regression model explained approximately 99.9% of the variation in sales.
- TV advertising had a statistically significant positive effect on sales.
- Increased investment in TV advertising was associated with increased expected sales.

## Business Recommendation

Based on the regression analysis, TV advertising should receive priority in marketing budget allocation due to its strong predictive relationship with sales.

A balanced strategy can still incorporate Radio and Social Media channels, but TV advertising demonstrated the highest potential return based on the analysis.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
