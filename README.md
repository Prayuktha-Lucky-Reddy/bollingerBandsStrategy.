# Bollinger Bands Trading Strategy

## Author
**Prayuktha Lucky Reddy**  
B.Tech Mathematics and Computing, IIT Indore

## Overview
This project implements a simple Bollinger Bands based trading strategy in a Jupyter Notebook. Historical stock data is obtained using Yahoo Finance, trading signals are generated using Bollinger Bands, and the strategy is backtested to evaluate its performance.

## Features
- Download historical stock data using Yahoo Finance
- Calculate Bollinger Bands
- Generate buy and sell signals
- Backtest the trading strategy
- Visualize stock prices, Bollinger Bands, and equity curve
- Calculate performance metrics such as:
  - Cumulative Return
  - Annualized Return
  - Sharpe Ratio
  - Sortino Ratio
  - Maximum Drawdown
  - Win Rate
  - Profit Factor
- Compare strategy performance against the Nifty 50 Index

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- yfinance

## File
- `bollinger_bands_strategy.ipynb` – Complete implementation, backtesting, visualization, and performance analysis.

## Results (FEDERALBNK.NS)
| Metric | Value |
|----------|----------|
| Cumulative Return | 78.56% |
| Annualized Return | 21.15% |
| Sharpe Ratio | 0.85 |
| Sortino Ratio | 0.80 |
| Maximum Drawdown | -18.54% |
| Win Rate | 100.00% |
| Profit Factor | ∞ |

## Disclaimer
This project is intended for educational and learning purposes only. It should not be considered financial advice.
