# Telecom Customer Churn Prediction
Dataset: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

## Project Overview
This project focuses on predicting customer churn using machine learning models. It explores different approaches, from Logistic Regression to Decision Trees, Random Forest, and finally, XGBoost, optimizing hyperparameters to achieve the best performance. The model helps businesses identify at-risk customers and take proactive retention measures.

## Project workflow

1. Data Preprocessing:
- Handled missing values, class imbalance, feature encoding, and scaling
2. Exploratory Data Analysis (EDA) to understand patterns
Baseline Model:
- Logistic Regression as the initial benchmark
3. Tree-Based Models:
- Decision Trees: High variance → prone to overfitting
- Random Forest: Reduced variance but required tuning
- XGBoost: Best trade-off between bias and variance
4. Hyperparameter Tuning:
- Used GridSearchCV to optimize model parameters
5. Final Model Performance:
- Training Accuracy: 88.6%
- Test Accuracy: 84.3%
- Balanced precision & recall for both classes
