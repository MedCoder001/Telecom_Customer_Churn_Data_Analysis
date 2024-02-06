# Telecom Churn Analysis Project

## Introduction
This project focuses on analyzing and understanding customer churn in the telecom industry using datasets obtained from Kaggle. Customer churn, which refers to customers discontinuing services with a company, poses a significant challenge for telecom service providers. By analyzing the factors contributing to churn and implementing effective strategies, telecom companies can mitigate churn rates and improve customer retention.

## Data Gathering
### Dataset 1:
- **Type:** CSV File
- **Method:** Direct download from Kaggle
- **Source:** [Telecom Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Variables:** CustomerID, Gender, Partner, Dependents, Tenure, PhoneService, MultipleLines, InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies, Contract, PaperlessBilling, PaymentMethod, MonthlyCharges, TotalCharges, Churn.

### Dataset 2:
- **Type:** Zipped CSV File
- **Method:** API approach via Kaggle
- **Source:** Kaggle
- **Variables:** Similar to Dataset 1.

## Data Assessment
- **Quality Issues:** Identified and resolved data quality issues such as converting column names to lowercase, replacing spaces with underscores, and removing unnecessary columns.
- **Missing Data:** Dropped rows with missing values in specific columns to ensure data completeness.

## Data Cleaning
- **Validity:** Ensured data validity by replacing specific values (e.g., "Fiber optic" and "DSL" with "Yes") and standardizing column values.
- **Completeness:** Addressed missing data issues by dropping rows with missing values.
- **Consistency:** Standardized column names and values for consistency across datasets.

## Data Analysis and Visualization
- Analyzed the impact of categorical and numerical variables on customer churn.
- Visualized churn rates by contract type and payment method.
- Provided insights into factors influencing churn behavior.

## Reflection
- Proposed future steps for advanced analysis, including feature engineering, machine learning modeling, customer segmentation, and dashboard development.
- Highlighted the goal of achieving substantial churn rate reduction and long-term profitability.

## Conclusion
This project provides valuable insights into customer churn in the telecom industry and outlines strategies to mitigate churn rates. By understanding customer behavior and preferences, telecom companies can enhance customer satisfaction and loyalty, leading to improved business outcomes.
