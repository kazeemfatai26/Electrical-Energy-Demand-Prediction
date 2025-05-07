# 📡 Electrical Energy Demand Prediction of a Base Transceiver Station using ARIMA

## 📘 Project Overview
This project investigates the energy demand of a Base Transceiver Station (BTS) using three years of time-series load data. An ARIMA-based model was developed and evaluated to forecast energy demand, with the goal of improving power planning and reducing outages caused by energy shortages.

---

## 🔍 Objectives
- Model and forecast BTS energy consumption using the ARIMA model.
- Compare prediction accuracy for daily vs. hourly load profiles.
- Propose a renewable energy system to meet the forecasted demand using HOMER Pro.

---

## 📈 Methodology
- **Data Collected:** 3 years of historical load usage.
- **Model Used:** ARIMA(0,1,0)(1,0,1)[7] (Seasonal ARIMA).
- **Tools:** Python (for ARIMA modeling), HOMER Pro (for energy system design).
- **Evaluation Metrics:**
  - MAPE: Mean Absolute Percentage Error
  - RMSE: Root Mean Squared Error
  - MSE: Mean Square Error

---

## 📊 Key Results
- **Daily Load Profile:**
  - MAPE: 7.67%
  - RMSE: 0.78
  - MSE: 0.62

- **Hourly Load Profile (Dec 1, 2023 – Feb 29, 2024):**
  - MAPE: 13.32%
  - RMSE: 0.63
  - MSE: 0.40

- The model showed better performance on the daily load profile in terms of MAPE, but hourly profile had lower RMSE and MSE.

---

## ⚡ Renewable System Design
- Modeled in **HOMER Pro**.
- Achieved **98% renewable energy penetration**.
- Delivered **zero unmet electrical load**.

---

## 🛠 Tools & Technologies
- Python
- pandas, statsmodels (for ARIMA modeling)
- HOMER Pro
- Git/GitHub

---

## 📌 Conclusion
The study demonstrates that ARIMA is effective for forecasting BTS energy demand. Combined with optimized energy system design, telecom operators can reduce outages and improve renewable energy adoption.

---

## 📁 Project Structure
