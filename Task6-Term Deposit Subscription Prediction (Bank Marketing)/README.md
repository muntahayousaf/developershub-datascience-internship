# Task 6: Term Deposit Subscription Prediction (Bank Marketing)

## 📌 Project Overview
This project aims to predict whether a bank customer will subscribe to a term deposit using machine learning techniques.  
The dataset contains customer demographic details, financial information, and campaign-related attributes.

We build classification models and evaluate them using performance metrics and explainability techniques.

---

## 🎯 Objective
- Predict customer subscription to term deposit (Yes / No)
- Compare Logistic Regression and Random Forest models
- Evaluate performance using F1 Score and ROC-AUC
- Use SHAP for model explainability

---

## 📊 Dataset Description
The dataset contains the following features:

- age: Customer age  
- job: Job type  
- marital: Marital status  
- education: Education level  
- balance: Account balance  
- housing: Housing loan status  
- loan: Personal loan status  
- contact: Contact communication type  
- duration: Last contact duration  
- campaign: Number of contacts performed  
- pdays: Days since last contact  
- previous: Previous contacts count  
- poutcome: Previous campaign outcome  
- y: Target variable (subscription yes/no)

---

## ⚙️ Workflow
1. Import Libraries  
2. Load Dataset  
3. Data Exploration (EDA)  
4. Data Preprocessing (Encoding)  
5. Train-Test Split  
6. Model Training  
   - Logistic Regression  
   - Random Forest  
7. Model Evaluation  
8. Explainable AI (SHAP)  
9. Insights & Conclusion  

---

## 📌 Key Results

### Model Performance Comparison

- Logistic Regression:
  - F1 Score: 0.255
  - ROC-AUC: 0.827

- Random Forest:
  - F1 Score: 0.367
  - ROC-AUC: 0.902

---

## 🧠 Key Insights

- Most customers do not subscribe to term deposits  
- Call duration is the strongest predictor  
- Previous campaign outcome strongly influences response  
- Customers with housing loans are less likely to subscribe  
- Random Forest performs better than Logistic Regression  

---

## 🔍 Explainability (SHAP)

SHAP analysis shows:
- Duration is the most important feature  
- Balance and contact type also influence predictions  
- Helps understand individual customer predictions  

---

## 🏁 Conclusion

This project demonstrates a complete machine learning pipeline including:
- Data preprocessing  
- Classification modeling  
- Performance evaluation  
- Explainable AI using SHAP  

Random Forest is the best performing model for this dataset.

---

## 🚀 Future Improvements
- Hyperparameter tuning  
- Handling class imbalance (SMOTE)  
- Feature engineering  
- Deployment using Flask or Streamlit
