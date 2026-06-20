# 🔋 Household Energy Consumption Forecasting

## 📌 Project Title
Time Series Forecasting of Household Electricity Consumption

---

## 🎯 Objective
The objective of this project is to analyze household electricity consumption patterns and forecast future energy usage using machine learning and time-series models.

---

## 📊 Dataset Information
This project uses the **Household Power Consumption Dataset**, which contains minute-level electricity usage data.

### Columns:
- Date
- Time
- Global_active_power
- Global_reactive_power
- Voltage
- Global_intensity
- Sub_metering_1
- Sub_metering_2
- Sub_metering_3

---

## ⚠️ Important Note (Dataset Not Uploaded)

❌ The original dataset is NOT uploaded to this GitHub repository.

### Reason:
- The file size exceeds GitHub upload limit (25MB / 100MB restriction)
- To avoid repository size issues, only code files are included

### How to Access Dataset:
You can download it from:
- Kaggle: Household Power Consumption Dataset
- Or use Google Drive / local system

---

## ⚙️ Project Workflow

### 1. Data Preprocessing
- Loaded semicolon-separated dataset
- Handled missing values ("?")
- Converted Date + Time into datetime format
- Set datetime as index

### 2. Feature Engineering
- Extracted:
  - Hour
  - Day of week
  - Weekend indicator
- Created lag features:
  - lag_1
  - lag_24

### 3. Resampling
- Converted minute-level data to hourly averages

---

## 🤖 Models Used

### 📊 ARIMA
- Statistical time series forecasting model

### 📈 Prophet
- Handles seasonality and trend automatically

### 🚀 XGBoost
- Machine learning model using lag + time features

---

## 📏 Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## 🏆 Results Summary

- ARIMA → Good for simple patterns
- Prophet → Good for seasonal trends
- XGBoost → Best performance overall

---

## 📉 Visualization
- Actual vs Predicted energy consumption
- Model comparison plots

---

## 🏁 Conclusion

This project demonstrates that machine learning models (especially XGBoost) outperform traditional statistical methods for energy forecasting when feature engineering is applied.

---

## 🚀 Tools Used
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
- Prophet
- XGBoost

---

## 👩‍💻 Author
Data Analytics / Machine Learning Project
