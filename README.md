S&P 500 Price Prediction using ARIMA

This project focuses on forecasting the **S&P 500 Index closing prices** using the ARIMA (AutoRegressive Integrated Moving Average) model. The notebook walks through data preprocessing, time series analysis, model building, and forecasting, and evaluates the model's performance with visual and statistical metrics.

## 📂 Project Structure
SP500_Price_Prediction.ipynb # Main Jupyter notebook with code and analysis
/plots # Saved figures and visualizations (optional)
/data # Data sources (CSV or external links)
README.md # Project overview and instructions


---

## 🧠 Key Features

- Converts raw S&P 500 daily data to business-day frequency
- Visualizes moving average and standard deviation
- Performs **Augmented Dickey-Fuller (ADF) test** to check stationarity
- Builds and trains an **ARIMA(2,1,1)** model
- Forecasts:
  - Close price for a specific day (e.g., **Monday, May 19, 2025**)
  - Price trends for the **next month**, **next 3 months**, and **until the end of 2025**
- Plots actual vs predicted values for easy comparison
- Evaluates model accuracy with **RMSE** and **MAE**

---

## 📊 Technologies & Libraries

- Python 3.11+
- pandas
- numpy
- matplotlib
- statsmodels
- scikit-learn

---

## 📌 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/SP500_ARIMA_Prediction.git
   cd SP500_Price_Prediction

## 📌 future features to be added to the model
1. Evaluation of ARIMA model
2. SARIMA/SARIMAX Forecast
3. META Prophet Price Prediction
4. Backtesting and cross-validation
5. Trading Bot
