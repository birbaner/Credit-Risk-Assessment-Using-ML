# Credit-Risk-Assessment-Using-ML

# Project Goal
Financial institutions like banks need to figure out if a borrower might not pay back their loan or credit card bill. This project uses machine learning (ML) to analyze this risk using real-world data from American Express.

The goal was to find the best model for predicting who might default (not pay back) and identify which factors (like credit score or spending habits) are most important.

**Dataset**

The data used in this project comes from the "AmExpert 2021 CODELAB - Machine Learning Hackathon" competition hosted on the online coding platform, HackerEarth. The dataset can be accessed here, belongs to American Express, a company that provides customers with various payment products and services.

The original dataset consisted of 45528 rows and 19 columns, but for this study, a subset of 30000 rows and 19 columns was used. The target variable of our data frame is “credit_card_default”, which is a binary variable, whose values are 0 and 1. Credit card default risk is the chance that companies or individuals will not be able to return the money lent on time. Data frame has 6 categorical features and 13 numeric features.

Dataset can be download at: https://www.kaggle.com/datasets/pradip11/amexpert-codelab-2021

**EDA - Feature Engineering - Modeling**

**Model	Accuracy**
Logistic Regression	0.9464
Random Forest	0.9650
Decision Tree	0.9663
LightGBM	0.9668
KNN	0.9681
CatBoost	0.9683
XGBoost	0.9734
