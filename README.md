# 🏦 Credit Risk Prediction

This project uses machine learning to predict whether a loan applicant is likely to **repay (Good)** or **default (Bad)** based on their financial and credit history.

---

## 📌 Objective

To help financial institutions assess the **creditworthiness** of loan applicants and reduce default risk using data-driven predictions.

---

## 🔍 What It Does

- Takes applicant details like income, loan amount, credit history, employment status, etc.
- Trains a classification model (e.g., XGBoost, Random Forest, Logistic Regression)
- Predicts whether an applicant is **Good** (low risk) or **Bad** (high risk)
- Uses **SHAP** to explain why a prediction was made

---

## ⚙️ How It Works

1. Load and clean credit data
2. Explore features and correlations
3. Train ML models: Logistic Regression, Random Forest, XGBoost
4. Evaluate performance (Accuracy, Confusion Matrix)
5. Visualize feature importance and explain predictions using SHAP

---

## 📊 Features Used

- Credit amount and duration  
- Credit history  
- Employment length  
- Housing type  
- Age, income, marital status  
- Purpose of the loan  

---

## 🧪 Sample Output

| Applicant | Credit Score | Loan Amount | Prediction |
|-----------|--------------|-------------|------------|
| A         | 680          | $3000       | Good       |
| B         | 580          | $7500       | Bad        |

---

## Key Tools
Python
Pandas, NumPy
Scikit-learn, XGBoost
SHAP (for explainability)
Jupyter Notebook

## 📈 Outcome
Predicts loan applicant risk accurately
Shows top features influencing each decision
Useful for banks, fintech lenders, and credit bureaus
