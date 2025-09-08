# Quant Stock Analysis

This project performs a basic quantitative analysis of historical stock prices using Python. It demonstrates data collection, visualization, and risk-return analysis for selected stocks.

## Data Source

- Historical daily stock prices are pulled from **Yahoo Finance** via the [`yfinance`](https://pypi.org/project/yfinance/) Python library.
- Adjusted Close prices are used to account for dividends and stock splits.

## Objectives

The project aims to:

1. Visualize normalized stock prices over time.
2. Identify trends using **short-term and long-term moving averages (SMA)**.
3. Measure volatility (annualized and rolling) to assess market risk.
4. Compare risk-adjusted performance via **Sharpe ratios**.
5. Understand correlations between stocks for portfolio insights.

## Analysis Outputs

### Normalized Prices
Shows how each stock has performed relative to its starting price, allowing direct comparison of growth over time.

### Moving Averages
- Short-term SMA crossing above long-term SMA indicates a bullish trend.
- Short-term SMA crossing below long-term SMA indicates a bearish trend.

### Volatility
- Annualized volatility highlights risk levels for each stock.
- Rolling volatility shows periods of higher market fluctuations.

### Risk-Adjusted Returns
- Sharpe ratio identifies which stocks performed better relative to the risk taken.

### Correlation (if implemented)
- Shows how stock prices move in relation to each other, useful for diversification.

##Lord Arday
