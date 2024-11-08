# Churn Prediction MLflow Databricks-Azure

This repository contains a complete machine learning pipeline for predicting customer churn, leveraging the Telco Customer Churn dataset from Kaggle. The project covers data cleaning, model training, evaluation, and model tracking using MLflow, with results stored in Databricks and Azure.

*This project serves as a practical example of building a churn prediction system, which is widely applicable in industries where retaining customers is critical. Predicting churn helps businesses:*

- Identify customers at risk of leaving
- Enable targeted retention efforts, reducing customer acquisition costs
- Improve overall customer satisfaction by proactively addressing potential issues
  
The integration of MLflow, Databricks, and Azure adds robust tracking, model management, and scalability to the pipeline, which are essential for production-ready machine learning workflows.

------------------------------------------------------------------------------------------------------------

## Dataset

The dataset used in this project is the Telco Customer Churn dataset from Kaggle, which includes customer information from a telecommunications company. Each row represents a customer, and the columns represent various attributes such as customer demographics, account information, and services. The target variable is Churn, indicating whether the customer left the company or not.

link: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

------------------------------------------------------------------------------------------------------------

## Project Workflow

### 1. Data Cleaning
The dataset is first preprocessed in the Data_Cleaning.ipynb notebook, which performs the following steps:

- Handling missing values
- Converting categorical variables into numerical representations
- Casting values
- Dropping columns

### 2. Model Training and Evaluation
Five machine learning models were trained to predict customer churn. The models were compared, and the best-performing one was selected based on key metrics such as accuracy, F1 score, and recall. The models and results are logged using MLflow, allowing for easy comparison and tracking.

![image](https://github.com/user-attachments/assets/760339a8-6fbe-48c7-adac-8130dce877fa)
