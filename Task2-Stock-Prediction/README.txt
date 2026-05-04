# Task 2: Stock Price Prediction using LSTM

### 🎯 Objective
The goal is to predict future stock prices based on historical data. Unlike standard regression, this requires capturing time-series patterns.

### 📊 Dataset
- **Source:** Yahoo Finance API (`yfinance`) or a CSV of historical stock data (e.g., AAPL or GOOGL).
- **Features:** Open, High, Low, Close, and Volume.

### 🛠 Methodology
- **Model:** Long Short-Term Memory (LSTM) network, which is a type of RNN (Recurrent Neural Network) designed for sequence data.
- **Preprocessing:** Applied **MinMaxScaler** to normalize data between 0 and 1 for better neural network convergence.
- **Evaluation:** Compared Predicted vs. Actual prices using Line Charts.

### 📈 Key Results
- The LSTM model successfully captured the general trend (uptrend/downtrend) of the stock.
- Observed that while LSTMs are powerful, stock markets are highly volatile and influenced by external news (sentiment).