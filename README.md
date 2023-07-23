# Loan Default Prediction Project

## Overview
Loan default prediction is a machine learning project aimed at helping lenders and banks identify borrowers who are likely to default on their loans. The project focuses on developing a predictive model based on various factors, such as income, credit history, loan amount, and demographic information.

## Dataset
The dataset used in this project can be downloaded from [Kaggle](https://www.kaggle.com/datasets/qusaybtoush1990/machine-learning?resource=download). It contains comprehensive information about credit applicants, making it valuable for developing loan approval prediction models.

### Features
The dataset consists of the following features:

- annual_inc: The annual income of the credit applicant.
- emp_length_num: The number of years of employment for the applicant.
- dti: The debt-to-income ratio of the applicant, which is the ratio of debt payments to income.
- revol_util: The revolving line utilization rate, representing the amount of credit used relative to the total available credit.
- total_rec_late_fee: The total late fees received by the applicant.
- od_ratio: The overall credit utilization ratio of the applicant.
- grade: Loan grade assigned by the lender based on the applicant's creditworthiness.
- home_ownership: The type of home ownership, including categories like 'OWN', 'RENT', 'MORTGAGE', etc.
- purpose: The purpose of the loan, such as 'debt consolidation', 'credit card', 'home improvement', etc.
- term: The term duration of the loan, either '36 months' or '60 months'.
- last_major_derog_none: Indicates whether the applicant has any major derogatory public records (contains many NULL values).

### Target Variable
The target variable in this dataset is bad_loan, which is a binary feature indicating whether the applicant defaulted on the loan or not. A value of 1 indicates a loan default, and 0 indicates a successful repayment.

### Significance
The dataset's richness and the inclusion of crucial financial and demographic features make it highly relevant for developing a robust loan default prediction model. By exploring and analyzing this dataset, we aim to identify patterns and relationships that can help lenders and financial institutions make informed decisions while approving or denying loan applications, thereby mitigating the risk of loan defaults and optimizing their lending processes.

## Project Steps
1. **Data Exploration**: Analyzing the dataset's structure and distributions using visualizations to gain insights into the features and their relationship with loan defaults.

2. **Data Cleaning**: Handling missing values and resolving inconsistencies in the dataset to prepare it for further analysis.

3. **Data Preprocessing**: Standardizing numerical features and one-hot encoding categorical features to prepare the data for machine learning models.

4. **Model Development**: Training and evaluating several machine learning models for loan default prediction. The models include Logistic Regression, K Nearest Neighbors, Support Vector Machine, Decision Tree, Random Forest, and XGBoost.

5. **Model Evaluation**: Comparing the performance of different models based on accuracy, precision, and recall scores to determine the best model for predicting loan defaults.

## Results
The project concludes that both Support Vector Machine (SVM) and Logistic Regression models perform best for predicting loan defaults, based on their accuracy, precision, and recall scores.

Please note that the README summary only highlights the important details of the project. For a complete understanding of the implementation and analysis, please refer to the project's source code and documentation.

