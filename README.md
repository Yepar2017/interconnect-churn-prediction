## 🚀 Case study Highlights

- 🎯 Goal: Predict customer churn  
- 🧠 Model: Gradient Boosting  
- 📊 Performance: AUC-ROC > 0.91  
- 💡 Impact: Supports customer retention strategies  

# Customer Churn Prediction — Interconnect

## Overview
This case study focuses on predicting customer churn for a telecom company (Interconnect). The goal is to identify customers who are likely to leave the service, enabling the business to take proactive retention actions.

---

## Business Problem
Customer churn directly impacts revenue and growth. Acquiring new customers is significantly more expensive than retaining existing ones.

The company needs a reliable way to:
- Identify customers at risk of leaving
- Take action before churn happens
- Improve customer lifetime value

---

## Objective
Develop a machine learning model capable of predicting whether a customer will churn based on their service usage, contract details, and billing information.

---

## Data Description
The dataset includes:
- Customer demographics
- Contract type and tenure
- Internet and phone services
- Monthly and total charges

---

## Methodology

### 1. Data Preparation
- Cleaned inconsistent data types
- Handled missing values
- Converted categorical variables into numerical format

### 2. Exploratory Data Analysis
- Identified key churn drivers (contract type, tenure, charges)
- Analyzed class imbalance

### 3. Feature Engineering
- Created meaningful features to improve model performance

### 4. Model Training
Tested multiple models:
- Logistic Regression (baseline)
- Random Forest
- Gradient Boosting

---

## Results

- ✅ **Best Model:** Gradient Boosting  
- 📊 **AUC-ROC:** > 0.91  
- 📈 Strong ability to distinguish between churn and non-churn customers  

---

## Business Impact

This model enables the company to:

- Identify high-risk customers early  
- Design targeted retention strategies  
- Reduce customer loss and increase revenue  

💡 Even a small reduction in churn can lead to significant financial gains.

---

## Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## Key Takeaways

- Data quality and feature engineering had a major impact on performance  
- Tree-based models outperformed linear models  
- Model evaluation metrics (AUC-ROC) were critical for selection  

---

## 📊 Key Insights

### Churn Distribution
![Churn Distribution](Images/Distribution_Churn.PNG)

## Author

**Yezid Feria**  
Data Analyst | Data Science | Business Impact  
