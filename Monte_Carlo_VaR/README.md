# Monte Carlo Simulation for Value-at-Risk (VaR)

This notebook estimates **portfolio Value-at-Risk (VaR)** using **Monte Carlo simulation**, quantifying the potential maximum loss under probabilistic scenarios.

---

## 🎯 Objective
To simulate portfolio returns and estimate the potential downside risk at specified confidence levels (95% and 99%).

---

## ⚙️ Methodology
1. **Data Input:**  
   - Historical returns from selected equities.
2. **Simulation:**  
   - Generated random return paths using normal/lognormal distributions.
   - Conducted 10,000+ simulations to create a distribution of outcomes.
3. **Risk Estimation:**  
   - Calculated VaR at multiple confidence levels.
4. **Visualization:**  
   - Illustrated loss distributions, marking VaR thresholds.

---

## 📊 Core Concepts
- Value-at-Risk (VaR)  
- Monte Carlo Simulation  
- Confidence Intervals  
- Tail Risk Estimation

---

## 🧠 Insights
- Quantifies the probability of extreme portfolio losses.
- Highlights sensitivity of VaR to volatility assumptions.
- Demonstrates stochastic simulation as a robust risk management tool.

---

## 🧰 Tools & Libraries
`numpy` · `matplotlib` · `scipy.stats` · `seaborn`

---

## 🚀 Future Scope
- Add Conditional VaR (CVaR) analysis.
- Incorporate fat-tailed distributions for more realistic simulations.
- Automate reporting for daily VaR updates.
