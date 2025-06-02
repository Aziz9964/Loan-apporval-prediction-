# Loan-apporval-prediction-
Loan Approval Prediction using Random Forest Classifier
This project uses machine learning techniques to predict loan approval status based on applicant data. A Random Forest Classifier is trained on historical loan data to identify patterns that influence loan approval.

Project Overview

The objective is to build a model that accurately predicts whether a loan will be approved (Y) or not approved (N) based on features such as:

Applicant's income
Education
Credit history
Employment status
Property area
Loan amount
Dependents, etc.

Machine Learning Algorithm
Algorithm Used: Random Forest Classifier
Why?: It performs well on classification problems, handles both categorical and numerical data, and reduces overfitting via ensemble learning.

Dataset

The dataset contains loan application information with features like:

Gender
Married
Education
Self_Employed
ApplicantIncome
CoapplicantIncome
LoanAmount
Loan_Amount_Term
Credit_History
Property_Area
Dependents
Loan_Status (Target Variable)

Features Engineering

Missing values handled using mode and median imputation.
Categorical variables encoded using pd.get_dummies().
Columns like Loan_ID were dropped as they are non-informative.
Target variable: Loan_Status (Y/N)


