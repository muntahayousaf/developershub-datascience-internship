# 🛍️ Task 7 : Customer Segmentation Using K-Means Clustering

## 📌 Project Overview

This project focuses on customer segmentation using unsupervised learning (K-Means Clustering). The goal is to group customers based on their annual income and spending behavior so that businesses can understand customer patterns and apply targeted marketing strategies.

---

## 📊 Dataset

**Mall Customers Dataset**

### Features:
- CustomerID  
- Gender (Genre)  
- Age  
- Annual Income (k$)  
- Spending Score (1-100)  

---

## 🎯 Objective

- Perform Exploratory Data Analysis (EDA)
- Apply K-Means Clustering for segmentation
- Use PCA for visualization
- Identify meaningful customer groups
- Suggest marketing strategies for each segment

---

## ⚙️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🔍 Project Workflow

### 1. Data Loading
- Load dataset using pandas
- Inspect structure and missing values

### 2. Exploratory Data Analysis (EDA)
- Distribution of income and spending score
- Gender analysis
- Relationship between age, income, and spending

### 3. Feature Selection
- Annual Income
- Spending Score

### 4. Data Preprocessing
- Standard scaling applied

### 5. K-Means Clustering
- Elbow method used to find optimal clusters
- Customers grouped into segments

### 6. Visualization
- Scatter plots for clusters
- PCA used for 2D visualization

---

## 📊 Customer Segments Identified

- High Income High Spending Customers  
- High Income Low Spending Customers  
- Low Income High Spending Customers  
- Low Income Low Spending Customers  
- Medium Income Medium Spending Customers  

---

## 📌 Key Insights

- Customers naturally form different groups based on spending behavior.
- High income high spending customers are the most valuable.
- High income low spending customers need personalized marketing.
- Low income high spending customers respond strongly to discounts.
- Low income low spending customers contribute least to revenue.
- Medium customers represent stable regular buyers.

---

## 💡 Business Recommendations

- Focus premium strategies on high value customers.
- Target high income low spenders with personalized offers.
- Offer discounts to low income high spenders.
- Re-engage low value customers.
- Build loyalty programs for medium customers.

---

## 📈 Results

- Successfully segmented customers using K-Means.
- Clear clusters identified based on spending patterns.
- PCA helped visualize clusters in 2D space.

---

## 🚀 How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
