# Stock Prediction App

This project is a Streamlit-based web application for stock prediction. It uses the `yfinance` library to fetch historical stock data and the `prophet` library for time series forecasting. Users can select a stock from a predefined list, specify the prediction duration, and visualize both the raw and forecasted stock data. The app provides interactive charts and forecasting components to assist in making informed decisions about the selected stock.
![image](https://github.com/TechGeek-Mohit/stock-prediction/assets/101231709/69f4f80a-42c7-4ffd-9aeb-d72a6f1151c8)
![image](https://github.com/TechGeek-Mohit/stock-prediction/assets/101231709/07d15fe5-650c-4192-b4b9-eabfb9d4ce81)
![image](https://github.com/TechGeek-Mohit/stock-prediction/assets/101231709/984dd7a6-1f36-4efc-8ab8-b48a0508a604)
![image](https://github.com/TechGeek-Mohit/stock-prediction/assets/101231709/c8ac1963-19fc-4fdd-807a-b30fca9313ab)

## Usage

1. Install the required packages using the following command:

   ```bash
   pip install -r requirements.txt
   ```

2. Run the app using the Streamlit command:

   ```bash
   streamlit run main.py
   ```

## Features

- Select a stock from a list (e.g., AAPL, GOOG, MSFT) for prediction.
- Choose the number of years for forecasting.
- View raw historical stock data and a forecasted time series plot.
- Analyze forecast components, including trend and seasonality.

This app is designed to provide a user-friendly interface for stock prediction, making it accessible for both novice and experienced users.
