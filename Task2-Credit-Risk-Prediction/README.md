# 💳 Task 2: Credit Risk Prediction

## 📌 Objective

The objective of this project is to build a machine learning model that predicts whether a loan applicant is likely to default on a loan. This helps financial institutions assess risk and make informed lending decisions.

---

## 📦 Dataset

**Loan Prediction Dataset** (Kaggle)

The dataset contains information about loan applicants, including:

* Applicant Income
* Co-applicant Income
* Loan Amount
* Loan Term
* Credit History
* Education
* Property Area
* Loan Status

Target Variable:

* **Loan Status**

  * Approved
  * Rejected

---

## 🔧 Approach

### 1. Data Preprocessing

* Loaded and explored the dataset using Pandas.
* Identified missing values.
* Handled missing values using:

  * **Median Imputation** for numerical features.
  * **Mode Imputation** for categorical features.
* Checked data types and cleaned inconsistencies.

### 2. Exploratory Data Analysis (EDA)

Analyzed relationships between applicant characteristics and loan approval status through various visualizations.

### 3. Feature Engineering

* Encoded categorical variables using **LabelEncoder**.
* Prepared data for machine learning models.

### 4. Model Building

Implemented and compared two classification algorithms:

* Logistic Regression
* Decision Tree Classifier

### 5. Model Evaluation

Evaluated model performance using:

* Accuracy Score
* Confusion Matrix
* Classification Metrics

---

## 📊 Visualizations

| Visualization   | Purpose                                               |
| --------------- | ----------------------------------------------------- |
| Count Plot      | Loan approval vs rejection distribution               |
| Histogram + KDE | Distribution of loan amounts                          |
| Box Plot        | Loan amount comparison by education and loan status   |
| Scatter Plot    | Relationship between applicant income and loan amount |

---

## 💡 Key Insights

### 🏦 Credit History Matters Most

* Credit History emerged as the most influential feature for loan approval prediction.
* Applicants with a positive credit history had significantly higher approval rates.

### 💰 Income vs Loan Amount

* Applicants with higher incomes generally requested larger loans.
* However, higher income alone did not guarantee loan approval.

### 📈 Logistic Regression Performance

* Logistic Regression achieved approximately **80% accuracy**.
* It provided stable and interpretable results.

### 🌳 Decision Tree Performance

* Decision Trees captured non-linear relationships effectively.
* Depth limitation was necessary to reduce overfitting and improve generalization.

---

## 🤖 Machine Learning Models Used

### Logistic Regression

* Suitable for binary classification problems.
* Provides interpretable coefficients.
* Achieved strong baseline performance.

### Decision Tree Classifier

* Captures complex decision boundaries.
* Easy to visualize and interpret.
* Requires hyperparameter tuning to avoid overfitting.

---

## 📊 Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1 Score

---

## 🛠️ Skills Demonstrated

* Data Cleaning
* Missing Value Handling
* Exploratory Data Analysis (EDA)
* Feature Encoding
* Binary Classification
* Machine Learning Model Training
* Model Comparison
* Confusion Matrix Analysis
* Performance Evaluation

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

This project demonstrates the complete machine learning workflow, from data preprocessing and exploratory analysis to model training and evaluation. Logistic Regression provided strong predictive performance, while Decision Trees highlighted the importance of handling model complexity to prevent overfitting. The analysis confirms that credit history plays a critical role in loan approval decisions.

---
