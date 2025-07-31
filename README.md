# Stock Price Predictor with LSTM

This project predicts the future stock prices using historical data and an LSTM (Long Short-Term Memory) neural network.

## Features

- Downloads historical data from Yahoo Finance using `yfinance`
- Preprocesses and scales data using MinMaxScaler
- Uses a 3-layer LSTM model with dropout for training
- Predicts future prices for user-defined days
- Prints prediction accuracy and future price estimates

## Setup

```bash
pip install -r requirements.txt
python src/predict_stock.py
```
