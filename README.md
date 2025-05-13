# Spoty — Time Series Forecasting Playground

This repository is a personal lab for exploring **time series prediction**, starting with Facebook's Prophet and expanding into more advanced models like **XGBoost**.

---

## 📂 Current Contents

- `prophet-test-1.ipynb`: First experiment using [Prophet](https://facebook.github.io/prophet/) for trend and seasonality forecasting.

---

## 🎯 Goals

- Understand and compare different forecasting models.
- Go beyond black-box modeling by experimenting with **feature engineering** and **tree-based methods**.
- Explore the strengths of **XGBoost** for time series:
  - Lag features
  - Rolling statistics
  - Custom train/test splits

---

## 🔜 Next Steps

- [ ] Implement time series forecasting using **XGBoost**
- [ ] Engineer lag, window, and date-based features
- [ ] Evaluate performance (e.g., RMSE, MAE)
- [ ] Compare results with Prophet

---

## 🛠️ Requirements

Install required packages:

```bash
pip install prophet xgboost pandas matplotlib scikit-learn
