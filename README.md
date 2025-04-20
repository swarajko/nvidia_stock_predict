# nvidia_stock_predict
This project uses machine learning models; 'Random Forest' and 'XGBoost' to predict the **next-day direction** of NVIDIA's stock price. The goal is to classify whether the stock will go **up or down** the following day based on historical data and technical indicators.

Data Source
- Stock data fetched using `yfinance` (Yahoo Finance)

Models Implemented
- **Random Forest Classifier**
- **XGBoost Classifier**

Features Used
- **Return**: Daily percentage return
- **Volatility**: 10-day rolling standard deviation of returns
- **Rolling Averages Ratios**: Price compared to its rolling average over 2, 5, 60, 250, and 1000-day windows
- Standard OHLCV: Open, High, Low, Close, Volume
