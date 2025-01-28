# Kwanza Tukule Data Analyst Assessment
## Overview
This repository contains my submission for the Kwanza Tukule Data Analyst Assessment. The analysis was conducted using Python and Jupyter Notebook to evaluate and derive actionable insights from the provided anonymized sales dataset.

## Contents
The repository includes the following files:
|-- README.md (This file)
|-- data_cleaning.ipynb Jupyter Notebook that handles data cleaning
|-- exploring_data.ipynb notebook that handles data exploration
|-- dashboard.png (Screenshot of the dashboard summarizing key insights)
|-- data.csv This is our sales data
|-- cleaned_data.csv This is the processed and cleaned data
|-- Advanced_analysis/
    |-- forcasting.ipynb notebook that forecast the total sales (Value) for the next 3 months.
    |-- customer_segmentation.ipynb notebook that Perform a segmentation analysis of businesses (Anonymized Business) based on their purchasing behavior
    |-- correlation.ipynb notebook that Examine relationships between Quantity and Value
    |-- anomaly_detection.ipynb Identify any unusual spikes or drops in sales performance


## Task Completed
1. Data Cleaning and preparation
- Inspected the dataset for missing values, duplicates, and inconsistent data types.
- Resolved identified issues and summarized the process.
- Added a new column, Month-Year, extracted from the DATE column. (Screenshot included in the notebook.)

2.  Exploratory Data Analysis (EDA)
- **Analyzed total sales (Quantity and Value) grouped by**:

    - Anonymized Category
    - Anonymized Business

- **Created visualizations, including bar charts and time-series plots, to show**:

    - Trends over time (Value and Quantity)
    - Top 5 products by Quantity and Value.

3. Advanced Analysis
- **Customer Segmentation**: Classified businesses into High, Medium, and Low Value groups based on:
    - Total Quantity purchased
    - Total Value contributed
    - Frequency of transactions
    - Recommendations for engaging each group were provided.

- **Forecasting**: Applied an ARIMA model to forecast sales (Value) for the next 3 months.
- **Anomaly Detection**: Identified unusual spikes or drops in sales and hypothesized possible reasons based on data patterns.
- **Correlation Analysis**: Examined relationships between Quantity and Value and provided insights into sales performance drivers.

4. Strategic Insights and Recommendations
- **Product Strategy**: Recommended a product category for marketing campaigns based on performance.
- **Customer Retention**: Suggested strategies to re-engage businesses with reduced purchase frequency.
- **Operational Efficiency**: Proposed improvements to inventory management and supply chain processes based on seasonal trends.

5. Dashboard and Reporting
- **Created an interactive dashboard summarizing**:
    - Total Quantity and Value by Anonymized Category.
    - Top-performing products and businesses.
    - Time-series chart of sales trends.
    - Segmentation summary of customer groups.
    - A screenshot of the dashboard is included in this repository.

## Tools and Libraries Used
### Python:
- **Pandas, NumPy**: Data manipulation and analysis.
- **Matplotlib, Seaborn**: Data visualization.
- **Statsmodels**: Time-series forecasting (ARIMA model).
- **Scikit-learn**: Customer segmentation.
- **Jupyter Notebook**: To organize and present the analysis.
- **Dashboard Tools**: Power Bi