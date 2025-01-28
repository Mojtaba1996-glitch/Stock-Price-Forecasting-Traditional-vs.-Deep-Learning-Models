# Stock-Price-Forecasting-Traditional-vs.-Deep-Learning-Models

## Overview  
This project demonstrates the forecasting of stock prices and market directions using a combination of traditional time series models (ARIMA), Random Forest(RF), and deep learning architectures (LSTM and GRU). It aims to provide insights into the performance and accuracy of various forecasting techniques using real-world stock market data.
## Features  
- **Data Sources**: Weekly stock price and volume data from Yahoo Finance for nine Thai stocks.  
- **Models Implemented**:
  - **ARIMA**: Traditional statistical model for time series forecasting.
  - **LSTM**: Long Short-Term Memory neural networks for sequential data processing.
  - **RF**: Random Forest is used for time series forecasting.
  - **GRU**: Gated Recurrent Units for efficient time-series predictions.
- **Dual Input Capability**: Incorporates both price and volume data for RF and LSTM.  
- **Metrics**: Comprehensive evaluation using:
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Error (MAE)
  - Mean Absolute Percentage Error (MAPE)
  - R-squared (R²)
  - Directional Accuracy  
- **Visualization**: Side-by-side comparison of actual vs. predicted prices with professional plots.
- **Outputs**:
  - Forecasted prices and directions.
  - Selected stocks based on predictions.
  - CSV exports of results for further analysis.

## Technologies  
- **Python Libraries**:
  - Data Processing: `pandas`, `numpy`, `yfinance`
  - Modeling: `statsmodels`, `tensorflow`, `keras`
  - Visualization: `matplotlib`, `seaborn`
  - **File Format**: [📘FORECASTING.ipynb](FORECASTING.ipynb)


## Results (Price forecasting)
**ARIMA**
[📘ARIMA model](arima_results.png) 




