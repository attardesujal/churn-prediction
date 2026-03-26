# Customer Churn Prediction | EDA & ML Classification

## Overview
End-to-end ML classification project predicting telecom customer churn
using EDA, preprocessing, and three ML models.

## Tech Stack
Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn · XGBoost · Jupyter

## Dataset
Telco Customer Churn — [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Project Steps
1. Exploratory Data Analysis (EDA)
2. Data Cleaning & Preprocessing
3. Model Training — Logistic Regression, Random Forest, XGBoost
4. Model Evaluation — Accuracy, F1, Precision, Recall
5. Feature Importance Analysis

## Results
| Model                | Accuracy | F1 Score | Recall |
|----------------------|----------|----------|--------|
| Logistic Regression  | 80.06%   | 59%      | 55%    |
| Random Forest        | 79.14%   | 56%      | 50%    |
| XGBoost              | 77.57%   | 55%      | 52%    |

## Key Insights
- Tenure has strongest negative correlation with churn (-0.35)
- Month-to-month contract customers churn the most
- Logistic Regression performed best — highest recall (catches most churners)

## How to Run
pip install -r requirements.txt
jupyter notebook notebooks/churn_analysis.ipynb
```

---

## ✅ Your Project is Complete!

Now update your resume with the GitHub link:
```
GitHub: https://github.com/attardesujal/churn-prediction
