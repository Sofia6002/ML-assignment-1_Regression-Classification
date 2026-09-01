# Machine Learning — Assignment I

This repository contains two supervised learning tasks completed for the Machine Learning course assignment: a **regression** task predicting used-car resale prices, and a **classification** task predicting bank customer churn. Each task includes a full EDA → model → evaluation pipeline in a Jupyter notebook, plus a written report.

## Repository Structure

```
├── Task_A_Car_Price_Prediction/
│   ├── car_price_prediction.ipynb        # EDA, model training & evaluation
│   └── Car_Price_Prediction_Report.docx  # Written report
│
└── Task_B_Bank_Churn_Prediction/
    ├── bank_churn_prediction.ipynb       # EDA, model training & evaluation
    └── Bank_Churn_Prediction_Report.docx # Written report
```

## Task A — Car Price Prediction (Multi-Linear Regression)

Predicts a used car's selling price from attributes such as showroom price, age, mileage, fuel type, seller type, and transmission, and identifies which of these are statistically significant predictors.

- **Dataset:** [Car Price Prediction Dataset](https://www.kaggle.com/datasets/bhavikjikadara/car-price-prediction-dataset) (Kaggle) — 301 records
- **Algorithm:** Multiple Linear Regression (OLS + scikit-learn)
- **Result:** R² = 0.7528, MAE = 1.47 Lakhs, RMSE = 2.52 Lakhs on the test set

## Task B — Bank Customer Churn Prediction (Logistic Regression)

Predicts whether a bank customer will churn based on demographic, account, and behavioural features, to help the bank flag at-risk customers for retention efforts.

- **Dataset:** [Bank Customer Churn Dataset](https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset) (Kaggle) — 10,000 records
- **Algorithm:** Logistic Regression
- **Result:** Accuracy = 0.808, ROC-AUC = 0.7748 on the test set

## Tech Stack

Python · pandas · NumPy · scikit-learn · statsmodels · Matplotlib · Seaborn
