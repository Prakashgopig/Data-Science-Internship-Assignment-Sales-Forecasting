# 🛍️ Sales Forecasting - Wiseanalytics Data Science Internship

This project was completed as part of the Wiseanalytics Data Science Internship. It involves building a robust sales forecasting pipeline using real-world retail data from Ecuador. The goal is to predict daily sales for each product family across multiple stores over a 15-day period.

---

## 📁 Dataset Overview

- `train.csv`: Historical daily sales data
- `test.csv`: Data for which predictions are needed
- `stores.csv`: Metadata about each store
- `oil.csv`: Daily oil prices affecting economic conditions
- `holidays_events.csv`: Information on local holidays and events

---

## 📊 Project Workflow

### 🔹 Part 1: Data Processing & Feature Engineering
- Merged datasets (`oil`, `stores`, `holidays`)
- Interpolated missing oil prices
- Created:
  - Time-based features (day, week, month, etc.)
  - Event flags (holiday, promotion, payday, earthquake)
  - Rolling statistics & lag features
  - Store-specific averages and top product families
- Conducted exploratory data analysis (EDA)

### 🔹 Part 2: Modeling & Forecasting
- Trained and compared the following models:
  - Baseline (naïve)
  - ARIMA
  - Random Forest
  - XGBoost
  - LSTM
- Evaluated using RMSE, MAPE, R²
- Visualized predictions and feature importance

---

## 🏆 Model Comparison Summary

| Model           | RMSE   | MAPE   | R²    |
|----------------|--------|--------|-------|
| Baseline       | ...    | ...    | ...   |
| Random Forest  | ...    | ...    | ...   |
| XGBoost        | ✅ Best | ✅ Best | ✅    |
| ARIMA (sample) | ...    | ...    | ...   |
| LSTM (sample)  | ...    | ...    | ...   |

---

## 💡 Key Insights

- **XGBoost** gave the best overall performance.
- **Holiday & promotion flags** were strong predictors of sales spikes.
- **Oil prices** showed moderate correlation with economic sales fluctuations.
- **Inventory & promotions** should be optimized around payday periods and top product families by cluster.

---

## 📂 Repository Structure


---

## ▶️ How to Run

1. Clone the repo:
```bash
#git clone https://github.com/yourusername/wiseanalytics-sales-forecasting.git

#cd wiseanalytics-sales-forecasting
#pip install pandas numpy matplotlib seaborn scikit-learn xgboost keras statsmodels
