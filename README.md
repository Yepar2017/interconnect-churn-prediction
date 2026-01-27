# Customer Churn Prediction — Interconnect

## Business Problem
Interconnect is a telecommunications company that wants to predict customer churn.  
If the company can identify customers who are likely to cancel their service, it can proactively offer promotions or special plans to retain them.

The main objective of this project is to build a machine learning model capable of predicting whether a customer will leave the company or not.

---

## Data Description
The dataset is composed of multiple files collected from different sources:

- `contract.csv`: contract information.
- `personal.csv`: customer personal data.
- `internet.csv`: internet services information.
- `phone.csv`: phone services information.

All datasets are joined using the `customerID` column.

The data includes:
- Contract type and duration.
- Monthly and total charges.
- Internet and phone services.
- Additional services such as online security, technical support, streaming, and cloud backup.

---

## Methodology
The project followed these main steps:

1. Data loading and merging from multiple sources.
2. Data cleaning and preprocessing:
   - Handling missing values.
   - Encoding categorical variables.
   - Feature engineering.
3. Exploratory Data Analysis (EDA).
4. Model training and evaluation:
   - Logistic Regression (baseline).
   - Random Forest.
   - Gradient Boosting.
5. Model selection using AUC-ROC as the main evaluation metric.

---

## Final Model and Results
The best performing model was **Gradient Boosting**, achieving:

- **AUC-ROC:** 0.91  
- **Accuracy:** ~0.87

This indicates that the model has strong predictive performance in identifying customers like
