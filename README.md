## Data Source
The historical price data for this project is sourced from **Yahoo Finance**, utilizing the `yfinance` library in Python. 
We fetched daily price information for various currency pairs, including:

### Top Trading Currency Pairs
- EUR/USD
- GBP/USD
- USD/JPY
- AUD/JPY
- USD/CAD

Additionally, we collect data for the following major stocks:

### Major Stocks
- Apple (AAPL)
- Microsoft (MSFT)
- Google (GOOGL)
- Amazon (AMZN)
- NVIDIA (NVDA)

The dataset spans from January 1, 2014, to September 15, 2024

### EDA
Exploratory Data Analysis was done to understand the trends in price data and the correlation between different forex currency pairs.

### Model Fitting
3 Machine (deep) learning models were fit on the historical dataset (Prophet model, Xgboost model and CNN-LSTM hybrid model)

### Model Evaluation and Backesting
Model performance was evaluated using RSME and MAE statistical metrics. Back Testin was also conducted on the historical data to ascertain the performance of CNN-LSTM model which was the best performing model

