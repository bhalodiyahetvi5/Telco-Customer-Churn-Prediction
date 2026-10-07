# Telco Customer Churn Prediction 🚀

An end-to-end Machine Learning project in Python using VS Code to predict customer churn based on IBM's Telco dataset.

## 📌 Project Overview
- **Objective:** Predict whether a customer will churn (leave the service) or remain loyal.
- **Dataset:** IBM Telco Customer Churn (7,043 entries)
- **Best Model:** Logistic Regression with **80.70% Accuracy**

## 🛠️ Tech Stack & Tools
- Python 3.14
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- VS Code & Jupyter Notebook

## 🚀 Workflow Steps
1. **Data Loading:** Flexible loader for local CSV or remote IBM URL.
2. **Data Cleaning:** Handle missing values in `TotalCharges`, drop `customerID`, and binary encode variables.
3. **EDA:** Identified that month-to-month contracts and higher monthly charges drive churn.
4. **Model Training:** Trained Logistic Regression (80.70%) and Random Forest (78.64%).
5. **Feature Importance:** Identified `MonthlyCharges`, `TotalCharges`, and `Contract` as top churn drivers.
