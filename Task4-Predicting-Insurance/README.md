# 🏥 Task 4: Predicting Insurance Claim Amounts

## 📌 Objective

The objective of this project is to predict medical insurance charges based on an individual's demographic and health-related information. Accurate cost prediction can help insurance companies assess risk and estimate claim expenses more effectively.

---

## 📦 Dataset

**Medical Cost Personal Dataset** (Kaggle)

The dataset contains personal and health-related information, including:

* Age
* Sex
* BMI (Body Mass Index)
* Number of Children
* Smoking Status
* Region
* Insurance Charges (Target Variable)

Target Variable:

* **Charges** — Medical insurance claim amount

---

## 🔧 Approach

### 1. Data Preprocessing

* Loaded and explored the dataset using Pandas.
* Checked for missing values and duplicates.
* Inspected feature distributions and data types.

### 2. Feature Encoding

* Applied **Label Encoding** to:

  * Sex
  * Smoker

* Applied **One-Hot Encoding** to:

  * Region

### 3. Exploratory Data Analysis (EDA)

Performed statistical and visual analysis to understand relationships between features and insurance charges.

### 4. Correlation Analysis

* Generated a correlation heatmap.
* Identified features with the strongest influence on insurance costs.

### 5. Model Building

Trained and compared two regression models:

* Linear Regression
* Random Forest Regressor

### 6. Model Evaluation

Evaluated model performance using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### 7. Prediction Analysis

Compared actual and predicted insurance charges through visualization to assess model accuracy.

---

## 📊 Visualizations

| Visualization   | Purpose                                      |
| --------------- | -------------------------------------------- |
| Histogram + KDE | Distribution of insurance charges            |
| Box Plot        | Insurance charges for smokers vs non-smokers |
| Scatter Plot    | BMI vs charges by smoking status             |
| Scatter Plot    | Age vs charges by smoking status             |
| Heatmap         | Feature correlation matrix                   |
| Scatter Plot    | Predicted vs actual charges                  |
| Bar Plot        | Feature importance ranking                   |

---

## 💡 Key Insights

### 🚬 Smoking Status Dominates Costs

* Smoking status is the strongest predictor of insurance charges.
* Smokers incur substantially higher medical costs than non-smokers.

### ⚖️ BMI and Smoking Interaction

* Customers with both a high BMI and smoking habit experience the highest insurance charges.
* This combination significantly increases health-related risks.

### 👥 Age Matters

* Age is the second most influential feature.
* Insurance costs generally increase as age increases.

### 📈 Model Performance

* Linear Regression achieved an **R² score of approximately 0.75**.
* Random Forest Regressor improved performance significantly with an **R² score of approximately 0.87**.

### 💰 Prediction Error

* Average prediction error (MAE) ranged between **$2,500 and $4,000**.
* Random Forest consistently produced more accurate predictions.

---

## 🤖 Machine Learning Models Used

### Linear Regression

* Simple and interpretable regression model.
* Establishes a strong baseline for prediction.
* Works well with linear relationships.

### Random Forest Regressor

* Ensemble learning algorithm.
* Captures complex, non-linear feature interactions.
* Provides feature importance analysis.
* Achieved the highest predictive performance.

---

## 📊 Evaluation Metrics

| Metric   | Purpose                            |
| -------- | ---------------------------------- |
| MAE      | Average prediction error           |
| RMSE     | Penalizes larger prediction errors |
| R² Score | Measures explained variance        |

---

## 🛠️ Skills Demonstrated

* Data Cleaning & Preprocessing
* Label Encoding
* One-Hot Encoding
* Exploratory Data Analysis (EDA)
* Correlation Analysis
* Regression Modeling
* Linear Regression
* Random Forest Regression
* Feature Importance Analysis
* Model Evaluation using MAE, RMSE, and R² Score
* Prediction Visualization

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

This project demonstrates a complete regression-based machine learning workflow for predicting medical insurance costs. Through exploratory analysis and model comparison, smoking status, BMI, and age emerged as the most influential factors affecting insurance charges. While Linear Regression provided a solid baseline, Random Forest Regressor delivered significantly better predictive performance, making it a strong choice for insurance cost estimation.

---
