# Stock Market Prediction using Machine Learning

This project uses historical stock market data (S&P 500) and machine learning models to predict whether the stock market will go up or down on the next trading day. The model leverages a **Random Forest Classifier** trained on a variety of technical indicators and features to forecast stock price movements.

## Features

- **Historical Data**: Downloaded using `yfinance` to retrieve the historical stock data for S&P 500.
- **Machine Learning**: Predicted stock market movement using Random Forest, with additional feature engineering (e.g., rolling averages, technical indicators).
- **Backtesting**: Built-in backtesting functionality to evaluate the model's performance over different time periods.
- **Performance Metrics**: Measures prediction accuracy using precision score and other classification metrics.

## Requirements

This project requires the following Python packages:

- `yfinance`
- `pandas`
- `sklearn`
- `matplotlib`
- `numpy`

You can install these dependencies using `pip` by running:

```bash
pip install -r requirements.txt
