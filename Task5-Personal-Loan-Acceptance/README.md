# 💰 Task 5: Personal Loan Acceptance Prediction

## 📌 Objective

The objective of this project is to predict which bank customers are most likely to accept a personal loan offer. By identifying potential customers, banks can improve marketing efficiency, increase conversion rates, and reduce campaign costs.

---

## 📦 Dataset

**Bank Marketing Dataset** (UCI / Kaggle)

The dataset contains information collected from direct marketing campaigns conducted by a banking institution.

**Important Note:**
The dataset uses a semicolon (`;`) as the separator and should be loaded accordingly.

Features include:

* Age
* Job
* Marital Status
* Education
* Default Status
* Housing Loan
* Personal Loan
* Contact Type
* Campaign Information
* Previous Marketing Outcomes

Target Variable:

* **y**

  * Yes = Accepted Personal Loan Offer
  * No = Did Not Accept Personal Loan Offer

---

## 🔧 Approach

### 1. Data Preprocessing

* Loaded the dataset using Pandas.
* Inspected data types and feature distributions.
* Identified placeholder values such as `"unknown"`.
* Replaced unknown values using mode imputation.

### 2. Feature Encoding

* Applied **Label Encoding** to categorical features.
* Converted all variables into machine-learning-ready numerical format.

### 3. Train-Test Split

* Used **stratify=y** during train-test splitting.
* Preserved class distribution between training and testing datasets.

### 4. Model Building

Trained and compared two classification algorithms:

* Logistic Regression
* Decision Tree Classifier

### 5. Model Evaluation

Evaluated model performance using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* ROC-AUC Score
* ROC Curve Analysis

### 6. Business Insight Extraction

Analyzed customer demographics and behavior patterns to identify customer segments most likely to accept loan offers.

---

## 📊 Visualizations

| Visualization    | Purpose                                             |
| ---------------- | --------------------------------------------------- |
| Bar Plot         | Acceptance rate by job type                         |
| Count Plot       | Loan acceptance by marital status                   |
| Histogram        | Age distribution by acceptance status               |
| Bar Plot         | Acceptance rate by education level                  |
| Confusion Matrix | Model prediction performance                        |
| ROC Curve        | Comparison of Logistic Regression and Decision Tree |

---

## 💡 Key Insights

### 📉 Class Imbalance

* Overall loan acceptance rate is approximately **11%**.
* The dataset is heavily imbalanced, making accuracy alone insufficient for evaluation.

### 🎓 High-Converting Customer Segments

* **Students** and **retired customers** demonstrate the highest loan acceptance rates.
* These groups respond more positively to marketing campaigns.

### 💍 Marital Status Impact

* **Single customers** are more likely to accept personal loan offers compared to married or divorced customers.

### 📈 Importance of ROC-AUC

* ROC-AUC provides a more reliable performance measure than accuracy for imbalanced datasets.
* It evaluates the model's ability to distinguish between accepting and non-accepting customers.

### 🎯 Business Recommendations

* Marketing campaigns should prioritize:

  * Students
  * Retired customers
  * Single individuals
* Targeted campaigns can improve conversion rates while reducing marketing costs.

---

## 🤖 Machine Learning Models Used

### Logistic Regression

* Effective baseline classifier.
* Produces interpretable results.
* Performs well on binary classification tasks.

### Decision Tree Classifier

* Captures non-linear relationships.
* Easy to interpret and visualize.
* Can overfit without proper tuning.

---

## 📊 Evaluation Metrics

| Metric           | Purpose                              |
| ---------------- | ------------------------------------ |
| Accuracy         | Overall prediction correctness       |
| Confusion Matrix | Breakdown of predictions             |
| Precision        | Quality of positive predictions      |
| Recall           | Ability to identify actual positives |
| F1 Score         | Balance between precision and recall |
| ROC-AUC          | Performance on imbalanced data       |

---

## 🛠️ Skills Demonstrated

* Data Cleaning & Preprocessing
* Handling Missing and Unknown Values
* Label Encoding
* Exploratory Data Analysis (EDA)
* Classification Modeling
* Logistic Regression
* Decision Tree Classification
* ROC-AUC Analysis
* Confusion Matrix Evaluation
* Business Insight Extraction
* Customer Segmentation Analysis

---

## 🧰 Technologies Used

| Library      | Purpose                                  |
| ------------ | ---------------------------------------- |
| pandas       | Data loading, cleaning, and manipulation |
| numpy        | Numerical operations                     |
| matplotlib   | Base plotting library                    |
| seaborn      | Statistical data visualization           |
| scikit-learn | Machine learning models and evaluation   |

---

## 📈 Conclusion

This project demonstrates a complete machine learning workflow for predicting personal loan acceptance. Through data preprocessing, exploratory analysis, classification modeling, and business interpretation, valuable customer insights were uncovered. The results highlight the importance of evaluating imbalanced datasets using ROC-AUC and suggest that targeted marketing toward students, retirees, and single customers can significantly improve loan campaign effectiveness.

---
