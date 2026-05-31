# 🏦 Task 3: Customer Churn Prediction (Bank Customers)

## 📌 Objective

The objective of this project is to predict whether a bank customer is likely to leave the bank (churn). Customer churn prediction helps financial institutions improve customer retention strategies and reduce revenue loss.

---

## 📦 Dataset

**Churn Modelling Dataset** (Kaggle)

The dataset contains information about bank customers, including:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Account Balance
* Number of Products
* Credit Card Status
* Active Membership Status
* Estimated Salary
* Churn Status (Target Variable)

Target Variable:

* **Exited**

  * 0 = Customer Stayed
  * 1 = Customer Churned

---

## 🔧 Approach

### 1. Data Preprocessing

* Loaded the dataset using Pandas.
* Inspected data structure and feature types.
* Checked for missing values and duplicates.
* Removed irrelevant identifier columns:

  * RowNumber
  * CustomerId
  * Surname

### 2. Feature Encoding

* Applied **Label Encoding** to:

  * Gender

* Applied **One-Hot Encoding** to:

  * Geography

### 3. Feature Scaling

* Used **StandardScaler** to normalize numerical features for Logistic Regression.

### 4. Model Training

Built and compared two machine learning models:

* Logistic Regression
* Random Forest Classifier

### 5. Model Evaluation

Evaluated model performance using:

* Accuracy Score
* Confusion Matrix
* Classification Report

### 6. Feature Importance Analysis

Used Random Forest feature importance scores to identify the most influential factors contributing to customer churn.

---

## 📊 Visualizations

| Visualization | Purpose                                                           |
| ------------- | ----------------------------------------------------------------- |
| Count Plot    | Churn rate by geography                                           |
| Count Plot    | Churn rate by gender                                              |
| Histogram     | Age distribution of retained vs churned customers                 |
| Box Plot      | Account balance comparison between retained and churned customers |
| Bar Plot      | Feature importance ranking                                        |

---

## 💡 Key Insights

### 📉 Churn Distribution

* Approximately **20%** of customers have churned.
* The dataset is moderately imbalanced but still suitable for classification tasks.

### 👥 Age Impact

* **Age** is the most influential feature in predicting churn.
* Older customers are more likely to leave the bank.

### 🌍 Geographic Differences

* Customers from **Germany** exhibit significantly higher churn rates compared to customers from France and Spain.

### 💰 Account Balance

* Customers with higher account balances tend to churn more frequently.
* High-value customers may require targeted retention strategies.

### 🌲 Model Performance

* Random Forest achieved approximately **86% accuracy**.
* It outperformed Logistic Regression by capturing more complex relationships in the data.

---

## 🤖 Machine Learning Models Used

### Logistic Regression

* Strong baseline classification model.
* Easy to interpret and implement.
* Benefits from feature scaling.

### Random Forest Classifier

* Ensemble learning algorithm.
* Handles non-linear relationships effectively.
* Provides feature importance analysis.
* Delivered the best overall performance.

---

## 📊 Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1 Score
* Feature Importance Scores

---

## 🛠️ Skills Demonstrated

* Data Cleaning & Preprocessing
* Label Encoding
* One-Hot Encoding
* Feature Scaling
* Exploratory Data Analysis (EDA)
* Supervised Machine Learning
* Logistic Regression
* Random Forest Classification
* Feature Importance Analysis
* Model Evaluation & Comparison

---

## 🚀 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📈 Conclusion

This project demonstrates an end-to-end customer churn prediction workflow using machine learning techniques. Through data preprocessing, feature engineering, model training, and evaluation, valuable insights were uncovered regarding customer behavior. The analysis highlights age, geography, and account balance as major churn drivers, while Random Forest proved to be the most effective predictive model for this dataset.

---
