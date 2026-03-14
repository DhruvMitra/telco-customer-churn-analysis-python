# telco-customer-churn-analysis-python
Exploratory data analysis of telecom customer churn dataset to uncover insights that help reduce customer attrition.

# Customer Churn Analysis using Python

    Project Overview

Customer churn is a major challenge for telecom companies. Losing customers directly affects revenue and growth.

This project analyzes a telecom dataset to identify patterns and factors that contribute to customer churn. The goal is to extract insights that help companies improve customer retention strategies.

    Dataset

The project uses the Telco Customer Churn Dataset, which contains information about telecom customers, their services, account information, and whether they churned.

Key dataset details:

Rows: ~7000 customers

Columns: 21 features

Target variable: Churn

    Main features include:

Customer demographics

Account information

Services subscribed

Monthly and total charges

    Project Objectives

The main objectives of this project are:

Perform data cleaning and preprocessing

Conduct exploratory data analysis (EDA)

Identify key factors influencing customer churn

Create data visualizations to understand patterns

Provide business insights to reduce churn

    Tools & Technologies Used

Python

Pandas – Data manipulation

NumPy – Numerical analysis

Matplotlib – Data visualization

Seaborn – Statistical visualization

Jupyter Notebook

    Project Workflow
1. Data Loading

The dataset was loaded using Pandas and the structure of the data was examined.

2. Data Cleaning

Data preprocessing steps included:

Handling missing values

Converting data types

Removing unnecessary columns

Checking for duplicates

3. Exploratory Data Analysis (EDA)

EDA was performed to identify patterns and relationships in the dataset.

Analysis included:

Churn distribution

Churn by contract type

Monthly charges vs churn

Tenure vs churn

Internet service vs churn

4. Data Visualization

Several visualizations were created to understand customer behavior and churn patterns.



    Key Insights

Some important insights discovered from the analysis:

Customers with month-to-month contracts have the highest churn rate

Snap 1: ![Image](https://github.com/user-attachments/assets/efa8712b-1178-4ece-adaf-d210a12b42fc)


Customers with higher monthly charges are more likely to churn

Snap 2: ![Image](https://github.com/user-attachments/assets/90c3f558-40f4-4696-9de4-2240445e240f)

New customers (low tenure) tend to leave more frequently

Snap 3: ![Image](https://github.com/user-attachments/assets/bc4dcb3b-71b8-4fc0-bc36-f9878d084094)


Customers without technical support or online security services show higher churn

Fiber optic internet users show relatively higher churn compared to other service types

Snap 4: ![Image](https://github.com/user-attachments/assets/50920327-b5a5-4a17-b133-ac3abf34022a)


    Business Recommendations

Based on the analysis, telecom companies can reduce churn by:

Encouraging customers to choose long-term contracts

Providing loyalty rewards for long-term customers

Improving customer support and service quality

Offering bundled service packages

Providing incentives for high monthly charge customers
