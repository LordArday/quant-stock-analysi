# Quant Stock Analysis — Starter

A clean, no-nonsense starter for a **Stock Price Data Analysis** project using Python, `yfinance`, and Jupyter Notebook. Perfect for a first-year quant project that shows data handling, time-series analysis, and plotting.

## What this does
- Pulls **daily price data** with `yfinance`
- Computes **moving averages (SMA 20/50)** and **volatility**
- Builds **daily returns** and a **correlation matrix**
- Plots normalized prices, SMAs, rolling volatility, and a correlation heatmap
- Saves tables and figures to the `output/` folder

## Quickstart

```bash
# 1) Create & activate a virtual env (recommended)
python -m venv .venv
# Windows:
.\.venv\Scripts\activate
# macOS / Linux:
# source .venv/bin/activate

# 2) Install dependencies
pip install -r requirements.txt

# 3) Launch Jupyter
python -m notebook
# ...then open notebook: notebooks/stock_analysis.ipynb
```

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

## What to deliver (for your CV/GitHub)
- A polished `README.md` (this file) describing your **approach, results, and what you learned**
- At least **3–4 clean charts** (already built by the notebook)
- A short **summary of insights** (e.g., “MSFT had the highest Sharpe in this period, correlations tightened in 2022–2023”, etc.)

## Push to GitHub (step-by-step)

1. Create a new GitHub repo (e.g. `quant-stock-analysis`), **no README/license/gitignore** (we already have them).
2. In a terminal inside this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: quant stock analysis starter"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```

## Next ideas
- Compare US vs. UK tickers
- Add **exponential moving averages** and **Bollinger Bands**
- Compute **CAGR, drawdown, Sharpe** per ticker
- Turn plots into a **report notebook** you can export to PDF
LORD ARDAY