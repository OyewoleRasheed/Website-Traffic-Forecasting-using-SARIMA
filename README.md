
# 📈 Website Traffic Forecasting using SARIMA

This project demonstrates how to model and forecast daily website traffic using time series analysis techniques — specifically the **SARIMA** model. The dataset includes daily visit counts to [thecleverprogrammer.com](https://www.thecleverprogrammer.com) from **June 2021 to June 2022**.

---

## 🗂️ Dataset

The dataset contains:
- **Date**: Daily timestamps
- **Views**: Number of website visits per daY

---

## ⚙️ Tools & Libraries
- `pandas`, `numpy` for data manipulation
- `matplotlib`, `seaborn` for visualization
- `statsmodels` for SARIMA modeling
- `scikit-learn` for performance evaluation

---

## 🔍 Key Steps
1. Data preprocessing & cleaning
2. Stationarity check (ADF Test)
3. Time series decomposition
4. SARIMA model fitting & forecasting
5. Evaluation of forecasting accuracy

---

## 📊 Forecast Output

The final output includes:
- Visual comparison of actual vs predicted traffic
- Forecast for future website visits
- RMSE and residual analysis
