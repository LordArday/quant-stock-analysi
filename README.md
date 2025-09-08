# Quant Stock Analysis — Starter

A clean, no-nonsense starter for a **Stock Price Data Analysis** project using Python, `yfinance`, and Jupyter Notebook. Perfect for a first-year quant project that shows data handling, time-series analysis, and plotting.

## What this does
- Pulls **daily price data** with `yfinance`
- Computes **moving averages (SMA 20/50)** and **volatility**
- Builds **daily returns** and a **correlation matrix**
- Plots normalized prices, SMAs, rolling volatility, and a correlation heatmap
- Saves tables and figures to the `output/` folder
> **Note:** Configure the tickers and date range near the top of the notebook. Default tickers are a few large-cap US tech names—swap for LSE tickers if you prefer (e.g., `'VOD.L'`, `'HSBA.L'`).

## Project Structure
```
quant-stock-analysis-starter/
├─ data/                 # (auto) CSV cache of raw downloads
├─ notebooks/
│  └─ stock_analysis.ipynb
├─ output/
│  ├─ figures/           # where charts are saved
│  └─ tables/            # metrics & correlation CSVs
├─ .gitignore
├─ LICENSE
├─ README.md
└─ requirements.txt
```
LORD ARDAY
