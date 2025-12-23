# intro-python-trading-spy

# Python for Finance: SPY Analysis, Technical Indicators & Simple Backtesting

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Libraries](https://img.shields.io/badge/Libraries-yfinance%20%7C%20pandas_ta%20%7C%20matplotlib-success)](https://github.com/ranaroussi/yfinance)
[![Udemy Course](https://img.shields.io/badge/Source-Udemy%20Course-orange)](https://www.udemy.com/course/python-for-trading-and-finance/)

## Overview

This repository contains my personal implementation and notes from the free Udemy course  
**"Python for Trading and Finance"** by [Genbox Trading](https://www.udemy.com/course/python-for-trading-and-finance/).

The project focuses on practical Python-based financial data analysis using real market data (primarily **SPY** — S&P 500 ETF, with ~50 years of history).  
It covers downloading data, calculating returns & volatility, creating technical indicators, simple rule-based backtesting, and intermarket correlation analysis (SPY vs TLT).

**Main topics demonstrated:**
- Historical price data retrieval with `yfinance`
- Daily returns, statistical analysis & distribution visualization
- Volatility regime analysis
- Technical indicators (RSI, SMA ratios, Williams %R) via `pandas_ta`
- Basic mean-reversion / trend-following backtest
- Rolling correlation between SPY and TLT (long-term Treasuries)
- Simple intermarket strategy based on negative correlation

## Requirements

- Python 3.8+
- Required libraries:
  ```bash
  pip install yfinance pandas_ta matplotlib numpy pandas


## Usage

The entire project lives in one Jupyter/Colab notebook:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/154FaaUH3cL8buPbTDIMLoRRbBBXfvSgV?usp=sharing)

1. Open the notebook in Google Colab (link above)
2. Run cells sequentially — everything (data download, calculations, plots) is self-contained
3. Explore the generated charts and backtest equity curves

## Key Analyses & Visualizations

- SPY historical close price
- Daily returns time series with ±1σ / ±2σ bands
- Returns distribution histogram
- High vs low volatility regime next-day returns
- RSI(2), RSI(14), Close/SMA(14), Close/SMA(30), Williams %R(10)
- Cumulative returns of simple RSI + SMA mean-reversion strategy
- 14-day rolling correlation between SPY and TLT
- Cumulative returns of negative-correlation-based intermarket strategy

## Current Status

This is a **direct follow-along** implementation from the Udemy tutorial for learning purposes.  
Future planned enhancements:
- Personal interpretation and commentary on the results / graphs
- Performance comparison (Sharpe ratio, max drawdown, etc.)
- Additional indicators & strategy variations
- Portfolio-level analysis
- Export to clean .py script + modular functions

## Credits & License

- Course: [Python for Trading and Finance](https://www.udemy.com/course/python-for-trading-and-finance/) by Genbox Trading (free tutorial)
- Data: Yahoo Finance via `yfinance` library
- Code style & structure inspired by the course — all credit goes to the original instructor

Feel free to fork, use as learning reference, or open issues/suggestions!

---
Last updated: December 2025
```

This version is clean, professional, transparent about being tutorial-based, gives proper credit, and looks attractive on GitHub with badges.  
Good luck with your repo — it's a great starting point for a finance/Python portfolio! 🚀
