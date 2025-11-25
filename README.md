# 🏦 Bank Customer Churn Analytics

This project is a complete end-to-end data analytics case based on a real business problem faced by retail banks: predicting and reducing customer churn.

The goal is to analyze customer behavior, build a churn prediction model, identify churn drivers, and provide actionable business recommendations.

---

## 📌 Project Overview

Customer churn is one of the most expensive problems in retail banking.  
Even a 2–3% increase in churn can lead to millions in lost revenue.

This project focuses on:
- identifying customers with the highest probability of leaving,
- understanding why they churn,
- designing solutions to improve customer retention.

---

## 📂 Repository Structure

├── data/  
│ └── bank_churn_dataset.csv  
├── notebooks/  
│ ├── eda.ipynb  
│ ├── modeling.ipynb  
│ └── business_insights.ipynb  
├── README.md  
└── requirements.txt  

---

## 📊 Dataset Description

The dataset contains **3,000 bank customers** with the following features:

| Feature | Description |
|--------|-------------|
| `client_id` | Unique client identifier |
| `age` | Customer age |
| `region` | Region of residence |
| `months_with_bank` | Customer tenure in months |
| `balance` | Average account balance |
| `transactions_last_month` | Number of transactions in the last month |
| `mobile_app_logins` | Logins to the mobile banking app |
| `support_calls` | Number of support center calls |
| `has_credit` | 1 if the customer has a credit product |
| `has_deposit` | 1 if the customer has a deposit |
| `service_fee` | Monthly service fee |
| `churn` | Target variable: 1 — churned, 0 — retained |

---

## 🎯 Business Problem

A rapid increase in customer churn has been observed in the retail banking segment.  
The task is to:

1. **Predict which customers are likely to churn**  
2. **Identify the key drivers influencing churn**  
3. **Provide business recommendations to reduce churn**

---

## 🔍 Approach

1. **Exploratory Data Analysis (EDA)**  
   - Feature distributions  
   - Correlation analysis  
   - Customer segmentation  

2. **Feature Engineering**  
   - Behavioral metrics  
   - Activity-based flags  
   - Ratio features  

3. **Modeling**  
   - Logistic Regression  
   - Random Forest  
   - Gradient Boosting (XGBoost / LightGBM)  

4. **Validation**  
   - ROC-AUC  
   - F1-Score  
   - Recall (sensitive for churn prediction)  

5. **Business Insights**  
   - Risk segments  
   - Drivers of churn  
   - Recommendations  

---

## 🧠 Key Insights

From the analysis, the main churn drivers typically include:

- Low mobile app activity  
- Drop in monthly transactions  
- High service fees  
- Frequent support center calls  
- Lack of additional products (no credit/deposit)  

These insights allow the bank to create targeted retention strategies.

---

## 🛠 Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook / Google Colab  

---

## 📎 Dataset

The dataset is located at: https://raw.githubusercontent.com/notice4/bank-customer-churn-analytics/refs/heads/main/data/bank_churn_dataset.csv  

