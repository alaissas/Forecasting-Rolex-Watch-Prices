# 🕰️ Rolex Price Prediction (2010–2027)

This project aims to analyze and forecast the average price of Rolex watches using time series modeling (ARIMA). By examining historical data from 2010 to 2024, the model predicts price trends for the upcoming years (2025–2027), offering insights for collectors, resellers, and luxury watch investors.

---

## 🎯 Aim

To develop a robust time series forecasting model that accurately predicts future Rolex prices using historical production and pricing data.

---

## ✅ Objectives

- Perform Exploratory Data Analysis (EDA) on Rolex price data.
- Clean, filter, and aggregate prices by production year.
- Visualize trends, distribution, and outliers.
- Apply time series decomposition to understand trend and noise.
- Use ARIMA for time series forecasting.
- Evaluate model performance using RMSE and MAE.
- Forecast average Rolex prices for 2025–2027.

---

## 🗂️ Dataset

- 📁 File: `df.csv`
- 📌 Columns used: `year_of_production`, `price`
- 📆 Years considered: **2010 to 2024**

> The dataset was cleaned by removing missing values and filtering for years ≥ 2010.

---

## 📈 Visualizations

- Price distribution and boxplots
- Yearly average price trends
- Time series decomposition
- ACF and PACF plots
- ARIMA model forecast with confidence intervals
- Forecast evaluation plots

---

## ⚙️ Tech Stack

- **Language**: Python 🐍
- **Libraries**:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `statsmodels`
  - `sklearn`

---

## 🔍 Methodology

1. **Data Cleaning & Aggregation**
2. **Exploratory Data Analysis**
3. **ARIMA Modeling**
4. **Train-Test Evaluation (Last 2 years)**
5. **Forecasting (2025–2027)**

Model Order Used: `ARIMA(1,1,1)`

---

## 📊 Evaluation

| Metric | Value |
|--------|-------|
| RMSE   | ✅ Low error |
| MAE    | ✅ Low deviation |

---

## 🔮 Forecast Highlights

The ARIMA model forecasts a steady increase in average Rolex prices for the years 2025 to 2027, consistent with historical luxury watch market trends.

---

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/alaissas/rolex-price-prediction.git
   cd rolex-price-prediction
