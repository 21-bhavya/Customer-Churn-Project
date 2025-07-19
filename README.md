
# 📊 Telecom Customer Churn Prediction

## 🔍 Project Overview

This project aims to analyze customer churn data from a telecom company and build machine learning models to predict whether a customer is likely to leave the company. Identifying churn helps businesses proactively engage at-risk customers and improve retention strategies.

---

## 🧾 Dataset

- **Source**: Kaggle Dataset
- **Filename**: `WA_Fn-UseC_-Telco-Customer-Churn.csv`  
- **Description**: The dataset contains 7,043 customer records and 21 features including:
  - Customer demographics (gender, senior citizen, etc.)
  - Account information (tenure, contract type, internet service)
  - Usage metrics (monthly charges, total charges)
  - **Target**: `Churn` (Yes/No)

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- XGBoost
  
---

## 📈 Key Steps in the Project

1. **Exploratory Data Analysis (EDA)**
   - Distribution of Churn
   - Class imbalance visualization
   - Feature correlations

2. **Data Preprocessing**
   - Handling missing and categorical values
   - Converting `TotalCharges` to numeric
   - Encoding categorical features
   - Train-test split

3. **Model Building**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - AdaBoost Classifier
   - Gradient Boost Classifier
   - XGBoost Classifier

4. **Model Evaluation**
   - Confusion Matrix
   - ROC AUC Score
   - F1-Score, Precision, Recall
   - ROC curves

5. **Insights**
   - Contract type, tenure, and charges influence churn the most.
   - Month-to-month customers with high charges are more likely to churn.

---

## ⚖️ Handling Class Imbalance

- Visualized the class imbalance (approx. 74% No churn, 26% Yes)
- Used `roc_auc_score` for robust evaluation

```

## 📝 Future Work

- Deploy the model via Flask or Streamlit

---
