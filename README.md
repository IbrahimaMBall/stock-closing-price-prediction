#  Stock Closing Price Prediction

This project explores machine learning models to predict the next-day closing prices of five major stocks: **AAPL, GOOGL, MSFT, AMZN, and TSLA**.

##  Overview
Historical stock data (2018–2023) was used to engineer lag-based and technical features, such as:
- Previous day close & volume
- Moving averages (MA5, MA10)
- Price range & gain
- Rolling volatility

Four regression models were developed and compared:
-  Linear Regression
-  Random Forest
-  Gradient Boosting Regressor (GBR)
-  XGBoost

Models were evaluated on:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² score

## 🚀 Results
| Model            | Best Performance |
|------------------|------------------|
| Linear Regression| R² > 0.96 |
| Random Forest    | R² ~ 0.74–0.91 |
| GBR              | R² ~ 0.82–0.91 |
| XGBoost          | R² ~ 0.84–0.94 |

 **XGBoost delivered the best performance overall**, especially on volatile stocks like TSLA.

##  Files
- `Predicting_Stock_Closing_Prices.ipynb` — full notebook
- `README.md` — project overview

##  Next Steps
- Engineer additional technical indicators (RSI, MACD, Bollinger Bands)
- Explore time-series specific models (ARIMA, LSTM)
- Hyperparameter tuning

