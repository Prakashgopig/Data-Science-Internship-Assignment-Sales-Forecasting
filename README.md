# 🛒 Retail Sales Forecasting - Wiseanalytics Internship Project

This project focuses on **sales forecasting** using real-world retail data from Ecuador, as part of a Data Science Internship at Wiseanalytics. The goal is to build predictive models that help forecast product-level sales across different stores and families.

---

## 🔍 Part 1: Data Processing & Feature Engineering

- Merged datasets: `train`, `test`, `stores`, `oil prices`, and `holidays`.
- Created time-based features: `day`, `month`, `weekofyear`, `payday`, `earthquake`, etc.
- Engineered lag features and rolling statistics (`lag_7`, `rolling_mean_7`, etc.)
- Marked promotions, top product families, and holiday effects.

---

## 📈 Part 2: Modeling & Evaluation

- **Baseline Model:** Previous day sales (Naïve forecast).
- **Models Implemented:**
  - Random Forest Regressor
  - XGBoost Regressor
  - ARIMA (per time series)
  - LSTM (deep learning time series forecasting)
- **Evaluation Metrics:**
  - RMSE
  - MAPE
  - R² Score

---

## 📊 Insights & Recommendations

- **Top Performing Model:** XGBoost
- **Key Drivers:** Holidays, promotions, oil prices, and paydays.
- **Business Suggestions:**
  - Align inventory strategy with promotional periods.
  - Monitor oil prices as a macroeconomic signal.
  - Prioritize top-performing product families by cluster.

---

## 📁 Files Included

- `train.csv`, `test.csv`, `stores.csv`, `oil.csv`, `holidays_events.csv`
- `processed_train.csv`: after feature engineering
- `Sales_Forecasting_Part1.ipynb`
- `Sales_Forecasting_Part2.ipynb`

---

## 🧠 Skills Highlighted

- Data Cleaning & Wrangling (Pandas, Numpy)
- Time Series Forecasting
- Feature Engineering
- Machine Learning (Sklearn, XGBoost)
- Deep Learning (LSTM with Keras)
- Data Visualization (Seaborn, Matplotlib)

---

## 📌 Note

This project was completed as part of a Data Science Internship with **Wiseanalytics** and demonstrates how data-driven insights can enhance retail planning and decision-making.
