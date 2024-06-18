# Project: Trading Strategy Backtester

## Overview

This project implements a backtesting framework for multiple trading strategies using Python, pandas, TA-Lib, and yfinance. It allows users to simulate and evaluate the performance of various trading strategies against historical market data.

### Installation
To run the project, ensure you have Python installed. Use pip to install the necessary libraries:

```bash
pip install pandas numpy ta-lib yfinance matplotlib
```
### Run the Backtester:

```bash
bkbase = BacktesterIterativo("ASML.AS", "yahoo", "2020-01-01", "2024-04-24", 5000, usar_spread=False)
bkbase.Estrategia_RSI_MACD()
```

### Strategies Implemented so far
 - Cruce SMA (Simple Moving Average Crossover)
 - Mean Reversion
 - Cruce RSI (Relative Strength Index Crossover)
 - Bollinger Bands with SMA Filter
 - Trend Change (Picos)
 - Candle Counter
 - Bollinger Bands with RSI
 - Aaron Oscilator
