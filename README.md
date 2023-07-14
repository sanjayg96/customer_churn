# Bank Customer Churn Prediction through Classification Modelling

## About
The revenue of banks takes a massive hit when their customers leave. Also, acquiring new customers can be costlier than retaining the existing ones. So, banks must identify customers likely to churn and take preventive measures to keep them.

This project aims to predict customer attrition using their demographic and bank-related data. An XGBoost classification model predicts the outcome.

## Data
The data used for this project is the ABC bank's [Customer Churn Dataset](https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset). It contains customer data of account holders at ABC Multinational Bank.

A dedicated binary column named "churn" is present in the data which takes the value 1 if a customer as churned and 0 otherwise. It is found that there is a **class imbalance problem** and synthetic data oversampling is used to handle this issue.

 ## Modelling
 Various classification models such as Logistic Regression, K-NN, Tree based Bagging and Boosting models were evaluated. XGBoost classifier had the best performance and was chosen as the final model.

 ### Suggested actions for mitigating churn
 By considering the observations and results from the EDA, modelling and feature importances, some actions are suggested to reduce customer churn. You may find those suggestions by scrolling down to the bottom section of the modelling notebook present in the path `notebooks/modelling.ipynb`.

 ## Tools and libraries used

Purpose | Tools/Libraries
---|---
Interactive Python Development | Jupyter Notebook
Exploratory Data Analysis (EDA) | Pandas Profiling (ydata-profiling)
Data visualizations | PyGWalker (Tableau alternative for Jupyter), Matplotlib, Seaborn
Data manipulation | Pandas
Data Oversampling | Imbalanced-Learn (SMOTE)
Feature transforms and Modelling | Scikit-Learn, XGBoost, LightGBM

