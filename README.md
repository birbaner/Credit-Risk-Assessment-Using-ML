# Credit-Risk-Assessment-Using-ML

# Project Goal
Financial institutions like banks need to figure out if a borrower might not pay back their loan or credit card bill. This project uses machine learning (ML) to analyze this risk using real-world data from American Express.

The **goal** was to find the best model for predicting who might default (not pay back) and identify which factors (like credit score or spending habits) are most important.

**Dataset**

The data used in this project comes from the **"AmExpert 2021 CODELAB - Machine Learning Hackathon"** competition hosted on the online coding platform, HackerEarth.

The original dataset consisted of 45528 rows and 19 columns, but for this study, a subset of 30000 rows and 19 columns was used.

The **target variable** of our data frame is **“credit_card_default”**, which is a binary variable, whose values are 0 and 1.

**Dataset can be download at: https://www.kaggle.com/datasets/pradip11/amexpert-codelab-2021**

# Steps Taken
**Exploratory Data Analysis (EDA):** Looked at the data to understand trends and clean it.
**Feature Engineering:** Improved the data by creating or modifying variables to better help the models.
**Modeling:** Tested several machine learning models to predict defaults.


**Which model was best?**
**The XGBoost model performed the best:**

Accuracy: 97% (correct predictions overall)

Precision: 91% (correctly identifying defaulters)

F1-Score: 91% (balancing precision and recall)

AUC: 92% (ability to distinguish between defaulters and non-defaulters)

**Other models also did well but were slightly less accurate:**

Logistic Regression: 94.6%

Random Forest: 96.5%

CatBoost: 96.8%
