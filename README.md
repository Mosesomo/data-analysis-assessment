# Kwanza Tukule Data Analyst Assessment
## Overview
This repository contains my submission for the Kwanza Tukule Data Analyst Assessment. The analysis was conducted using Python and Jupyter Notebook to evaluate and derive actionable insights from the provided anonymized sales dataset.

## Contents
The repository includes the following files:
|-- README.md # This file |-- data_cleaning.ipynb # Jupyter Notebook that handles data cleaning |-- exploring_data.ipynb # Notebook that handles data exploration |-- dashboard.png # Screenshot of the dashboard summarizing key insights |-- data.csv # This is our sales data |-- cleaned_data.csv # This is the processed and cleaned data |-- Advanced_analysis/ |-- forecasting.ipynb # Notebook that forecasts the total sales (Value) for the next 3 months |-- customer_segmentation.ipynb # Notebook that performs a segmentation analysis of businesses (Anonymized Business) based on their purchasing behavior |-- correlation.ipynb # Notebook that examines relationships between Quantity and Value |-- anomaly_detection.ipynb # Identify any unusual spikes or drops in sales performance


## Task Completed
1. Data Cleaning and preparation
- Inspected the dataset for missing values, duplicates, and inconsistent data types.
- Resolved identified issues and summarized the process.
- Added a new column, Month-Year, extracted from the DATE column. (Screenshot included in the notebook.)
  ![Image](https://github.com/user-attachments/assets/06c083e1-a480-426b-af4f-6b911b82ef6d)

2.  Exploratory Data Analysis (EDA)
- **Analyzed total sales (Quantity and Value) grouped by**:

    - Anonymized Category
      ![Image](https://github.com/user-attachments/assets/ecf76798-19b8-46f8-aded-0e2975c3d2e5)
    - Anonymized Business
      ![Image](https://github.com/user-attachments/assets/8e6c9d73-b8a5-4834-95cf-610709c33499)

- **Created visualizations, including bar charts and time-series plots, to show**:

    - Trends over time (Value and Quantity)
      ![Image](https://github.com/user-attachments/assets/1b7b4469-2d0c-4b9d-9ae5-022d931d9cb9)
    - Top 5 products by Quantity and Value.
      ![Image](https://github.com/user-attachments/assets/938def05-202e-4ce5-af4c-ac3014c4bc5a)

3. Advanced Analysis
- **Customer Segmentation**: Classified businesses into High, Medium, and Low Value groups based on:
    - Total Quantity purchased
    - Total Value contributed
    - Frequency of transactions
    - Recommendations for engaging each group were provided.

- **Forecasting**: Applied an ARIMA model to forecast sales (Value) for the next 3 months.
  ![image](https://github.com/user-attachments/assets/644820a8-37cf-4c3d-bf24-5e93d28cb71b)

- **Anomaly Detection**: Identified unusual spikes or drops in sales and hypothesized possible reasons based on data patterns.
  ![image](https://github.com/user-attachments/assets/22a06b50-470b-47a6-87e3-9d74b7fca5ec)

- **Correlation Analysis**: Examined relationships between Quantity and Value and provided insights into sales performance drivers.
  ![image](https://github.com/user-attachments/assets/4f363520-5aa6-4f36-85ff-18f42eb0b27c)


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
      ![image](https://github.com/user-attachments/assets/1043ba0b-159d-49b0-97a1-947da3e26cdb)


## Tools and Libraries Used
### Python:
- **Pandas, NumPy**: Data manipulation and analysis.
- **Matplotlib, Seaborn**: Data visualization.
- **Statsmodels**: Time-series forecasting (ARIMA model).
- **Scikit-learn**: Customer segmentation.
- **Jupyter Notebook**: To organize and present the analysis.
- **Dashboard Tools**: Power Bi
