# Optimal Portfolio Weights for Maximum Sharpe Ratio

This project uses modern portfolio theory to determine optimal asset weights that maximize the Sharpe Ratio.

## Methodology
- Downloaded stock data using `yfinance`.
- Computed daily returns, expected annual returns, and covariance matrix.
- Simulated 10,000 random portfolios to estimate efficient frontier.
- Identified portfolio with the maximum Sharpe Ratio.

## Tools & Libraries
`pandas`, `numpy`, `matplotlib`, `yfinance`

## Insights
- Demonstrates portfolio diversification principles.
- Quantifies risk-return trade-offs.
- Visualizes the efficient frontier interactively.
