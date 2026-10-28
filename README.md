Telco Customer Churn Prediction

Project Overview

This project predicts whether a telecom customer is likely to leave the company (churn) using machine learning. The goal is to identify customers at risk of leaving and help businesses improve customer retention.

Dataset

The dataset contains customer information, including:

Customer demographics

Services and subscriptions

Contract type and payment method

Tenure and monthly charges

Churn status

Dataset: Telco Customer Churn Dataset on Kaggle

Tools & Technologies

Python

Google Colab

Pandas and NumPy

Matplotlib and Seaborn

Scikit-learn

Machine Learning

Project Workflow

Loaded and explored the dataset.

Cleaned missing values in TotalCharges.

Performed exploratory data analysis (EDA).

Prepared categorical and numerical features.

Split the data into training and testing sets.

Trained machine learning classification models.

Evaluated model performance using accuracy, precision, recall, F1-score, and a confusion matrix.

Examined feature importance to understand factors associated with churn.

Machine Learning Models

Logistic Regression

Random Forest Classifier

Key Findings

Customers with month-to-month contracts showed higher churn counts in the exploratory analysis.

Contract type is a useful feature to investigate when studying customer churn.

Model evaluation metrics help assess how effectively the models identify customers who may leave.

Project Files

Telco_Customer_Churn.ipynb — notebook containing the analysis, preprocessing, model training, and evaluation.

Future Improvements

Tune model hyperparameters.

Compare additional classification algorithms.

Improve churn detection using recall and F1-score.

Develop a simple web app for customer churn predictions.

Author

Eman Malik
