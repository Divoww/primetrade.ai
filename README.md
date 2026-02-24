Crypto Sentiment vs Trader Performance Analysis

Overview

This project analyzes how Crypto market sentiment (Fear/Greed Index) impacts trader performance, risk, and behavior.

The analysis includes:

- Daily profitability comparison across sentiment regimes
- Win rate and trade efficiency analysis
- Risk assessment using PnL volatility and drawdown proxy
- Long/Short positioning behavior
- Trader segmentation (frequency, risk proxy, consistency)
- Actionable regime-based strategy insights

Files

- main.ipynb — Complete analysis notebook
- summary.md — Methodology, insights and actionable recommendations
- fear_greed_index.csv — Market sentiment data
- historical_data.csv — Trader transaction data

Setup

- Install required packages:

  pip install pandas numpy matplotlib seaborn scipy jupyter
  How to Run
  jupyter notebook

- Open and run:

  main.ipynb

  Run all cells sequentially from top to bottom.

Notes

- Drawdown is computed using cumulative PnL and rolling peak.
- Leverage is proxied using trade size and PnL volatility.
- All metrics are calculated at daily and trader levels.


NOTE - historical_data.csv could not be loaded due to large file size
