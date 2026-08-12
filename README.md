# E-commerce Exploratory Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on an e-commerce dataset to understand the data, identify patterns and trends, and detect potential outliers.

## Dataset

The dataset contains **1,200 records and 14 columns**, including information about orders, customers, products, prices, payment methods, order status, and other order-related details.

## Analysis Performed

The following analysis was performed using Python:

- Dataset overview and information
- Descriptive statistics
- Univariate analysis
- Bivariate analysis
- Outlier detection using the IQR method
- Key findings and observations

## Key Findings

- The dataset contains 1,200 records with no missing values.
- Printer was the most frequently ordered product.
- Online payment was the most frequently used payment method.
- Phone had the highest average Unit Price, while Desk had the lowest.
- Total Price contained 8 upper outliers and no lower outliers.
- Unit Price contained no IQR outliers.
- The identified Total Price outliers were retained because they were associated with relatively high quantities and unit prices.

## Tools & Libraries

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Conclusion

The analysis provided an overview of the e-commerce dataset, highlighted important patterns across different variables, and identified unusually high Total Price values using the IQR method.
