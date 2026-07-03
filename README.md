 Hybrid time-series forecasting model that combines ARIMA and LSTM to predict multi-step NIFTY50 stock prices. The project integrates statistical modeling with deep learning to improve forecasting performance and evaluates predictions using a quantitative trading strategy.

## Features

- Hybrid ARIMA + LSTM forecasting framework
- Time-series preprocessing and stationarity analysis (ADF test)
- Seasonal decomposition and ACF/PACF-based parameter selection
- Multi-step stock price prediction
- Long/Short trading strategy backtesting on out-of-sample data
- Performance comparison against a passive buy-and-hold benchmark

## Results

- **Evaluation Period:** 493 trading days
- **Directional Accuracy:** 52.3%
- **Strategy Return:** 17.40%
- **Outperformed Buy-and-Hold By:** 7.8%
