GARCH vs EGARCH Volatility Forecasting

Small project comparing GARCH(1,1) and EGARCH on SPY data.

What I did
- Pulled SPY data from Yahoo Finance
- Computed log returns (scaled)
- Split into 80% train / 20% test
- Ran rolling 1-step ahead forecasts (refit each time)
- Compared using MSE and MAE
- Also checked performance in high vs low volatility periods
Output
- Model summaries
- Error comparison (MSE, MAE)
- Plots of predicted vs actual volatility
- Extra breakdown by volatility regime
Notes To Reader
- Using squared returns as a proxy for volatility
- Rolling refit is slow but I wanted to understand it properly
- Mostly just a learning project to get more comfortable with GARCH models
