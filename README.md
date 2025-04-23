
---

## 🧠 Problem Overview

Telecom companies face high customer acquisition costs, making customer retention a key priority. Using historical customer data, this project aims to:

- Understand which features correlate most with customer churn
- Train machine learning models to predict churn
- Deliver actionable insights to reduce churn rates

---

## 🔁 Workflow Summary

### ✅ 1. Data Preprocessing
- Convert object types to categorical/numerical
- Handle missing values
- Encode categorical variables

### ✅ 2. Exploratory Data Analysis (EDA)
- Churn distribution
- Feature-wise churn analysis
- Correlation heatmaps and bar charts

### ✅ 3. Feature Engineering
- Encode contract/payment types
- Create new features like `tenure_group`
- Scale continuous variables

### ✅ 4. Modeling
- Logistic Regression
- Random Forest
- (Optionally) Support Vector Machine, XGBoost

### ✅ 5. Model Evaluation
- Accuracy, Precision, Recall
- Confusion Matrix
- ROC-AUC Curve

---

## 🧰 Tech Stack

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## ✨ Key Insights

- Month-to-month contracts have the highest churn risk
- Customers with fiber optic internet and no tech support are more likely to churn
- Tenure and contract type are strong predictors

---

## 🔧 Possible Enhancements

- Handle class imbalance using SMOTE or class weights
- Deploy using Streamlit or Flask as a web app
- Add SHAP values or feature importance explanations


