# Optimal Portfolio Weights for Maximum Sharpe Ratio

This project applies **Modern Portfolio Theory (MPT)** to determine the combination of assets that delivers the **maximum Sharpe Ratio** — the optimal trade-off between return and risk.

---

## 🎯 Objective
To build an optimal investment portfolio using historical stock data and identify asset weights that **maximize risk-adjusted returns**.

---

## ⚙️ Methodology
1. **Data Collection:**  
   - Extracted historical price data using `yfinance` for a selected basket of Indian equities.
2. **Return & Risk Calculation:**  
   - Computed daily returns, expected annual returns, and covariance matrix.
3. **Simulation:**  
   - Generated thousands of random portfolios to estimate the **efficient frontier**.
4. **Optimization:**  
   - Applied mathematical optimization to identify the portfolio with **maximum Sharpe Ratio**.
5. **Visualization:**  
   - Plotted the efficient frontier with color-coded Sharpe Ratios.

---

## 📊 Core Concepts
- Sharpe Ratio  
- Covariance Matrix  
- Efficient Frontier  
- Portfolio Diversification

---

## 🧠 Insights
- Demonstrates diversification benefits among correlated assets.
- Quantifies the risk-return trade-off visually and numerically.
- Provides a scalable framework to optimize portfolios for any asset set.

---

## 🧰 Tools & Libraries
`pandas` · `numpy` · `matplotlib` · `yfinance` · `scipy.optimize`

---

## 🚀 Future Scope
- Add dynamic rebalancing and rolling Sharpe estimation.
- Integrate constraints (sector, weight limits, etc.) for realistic modeling.
