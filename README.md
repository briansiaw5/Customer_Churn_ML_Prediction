# Customer Churn Prediction using Machine Learning

## Project Overview

A telco company aims to increase its profit margins by focusing on customer retention. As data analysts for the company, our task is to build a machine learning model to predict customer churn. This project involves identifying the likelihood of a customer leaving the organization, determining key indicators of churn, and implementing retention strategies.

## Problem Statement

Customer attrition, or churn, represents a significant expenditure for organizations. Our objective is to analyze customer churn, identify key indicators influencing it, and build a model to predict churn rates.

## Objectives

1. Data Collection & Cleaning: Gather and preprocess customer data from various sources.
2. Exploratory Data Analysis (EDA): Understand underlying patterns and trends in the data.
3. Feature Engineering: Create relevant features to improve the model's predictive power.
4. Model Building: Develop and train machine learning models to predict customer churn.
5. Model Evaluation: Evaluate model performance using appropriate metrics.
6. Recommendations: Provide actionable insights and recommendations to the Telco company to reduce churn.

## Analytical Questions

1. What are the primary factors influencing customer churn in the company?
2. What demographic factors influence customer churn?
3. How does contract type affect the likelihood of customer churn?
4. How does tenure affect customer churn?
5. What is the impact of monthly charges and total charges on customer churn?

## Hypotheses

- **Null Hypothesis (H0)**: There are no significant differences in churn among the feature columns.
- **Alternate Hypothesis (H1)**: There are significant differences in churn among the feature columns.

## Data Understanding

The dataset is divided into three parts:
- **Training Data**: Two datasets used for training and evaluating the machine learning model.
- **Testing Data**: One dataset used for testing the model.

### Data Dictionary

The dataset is in CSV format with the following columns:

- `customerID`: Customer identifier.
- `gender`: Customer gender (Male/Female).
- `SeniorCitizen`: Whether the customer is a senior citizen (0 or 1).
- `Partner`: Whether the customer has a partner (True/False).
- `Dependents`: Whether the customer has dependents (True/False).
- `tenure`: Number of months the customer has stayed with the company.
- `PhoneService`: Whether the customer has phone service (True/False).
- `MultipleLines`: Whether the customer has multiple lines (True/False).
- `InternetService`: Customer's internet service provider (DSL, Fiber optic, No).
- `OnlineSecurity`: Whether the customer has online security (True/False).
- `OnlineBackup`: Whether the customer has online backup (True/False).
- `DeviceProtection`: Whether the customer has device protection (True/False).
- `TechSupport`: Whether the customer has tech support (True/False).
- `StreamingTV`: Whether the customer has streaming TV (True/False).
- `StreamingMovies`: Whether the customer has streaming movies (True/False).
- `Contract`: The contract term of the customer (Month-to-month, One year, Two year).
- `PaperlessBilling`: Whether the customer has paperless billing (True/False).
- `PaymentMethod`: The customer's payment method (Electronic check, Mailed check, Bank transfer, Credit card).
- `MonthlyCharges`: The amount charged to the customer monthly.
- `TotalCharges`: The total amount charged to the customer.
- `Churn`: Whether the customer churned (True/False).

## Project Steps

### Business Understanding

Understand the business problem and define the objectives and analytical questions.

### Data Understanding

Load and explore the dataset. Check for missing values, duplicates, and unique values.

### Data Preparation

Clean the data by handling missing values, encoding categorical variables, and normalizing numerical features.

### Modeling and Evaluation

Build and evaluate different machine learning models to predict customer churn.

### Recommendations

Recommend ways to deploy the model for utilization and integration with the business processes.

## Installation

To run the project, you need to install the required Python packages:

```sh
pip install pyodbc python-dotenv pandas numpy seaborn matplotlib statsmodels
```

## Usage

1. Clone the repository:
    ```sh
    git clone https://github.com/briansiaw5/Customer_Churn_ML_Prediction.git
    cd Customer_Churn_ML_Prediction
    ```

2. Run the notebook to load, clean, and analyze the data.

3. Build and evaluate the machine learning model.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

