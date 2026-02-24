METHODOLOGY
- Cleaned and validated both datasets (missing values, duplicates, date alignment).
- Aggregated trade-level data into daily and trader-level metrics (PnL, win rate, trade size, frequency).
- Merged sentiment classification with trading data.
- Compared performance and risk across regimes.
- Segmented traders by frequency, risk proxy, and consistency for behavioral analysis.

3 CORE INSIGHTS
- Extreme Fear = most trades, lowest win rate, highest total daily profits (some trades are highly profitable)
  Extreme Greed = lesser trades, higher win rate, highest profit per trade (consistent profits)
- Traders open more shorts during greed regimes and more longs during fear regimes.
- Extremely large trades (outliers) occur during Extreme Greed times which heavily skew the average.

2 ACTIONABLE OUTPUTS
- Cap maximum position size during Extreme Greed regimes.
- During Fear regimes, tilt strategy bias toward long setups with controlled downside risk.