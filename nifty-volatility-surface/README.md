# NIFTY 50 Implied Volatility Surface

This project constructs an implied volatility surface for **NIFTY 50 index call options**
using short-dated weekly expiries. Implied volatility is **back-calculated from market
prices** using the Black–Scholes framework rather than relying on exchange-published IV.

---

## Data
- **Underlying:** NIFTY 50 index  
- **Expiries:** 20 Jan, 27 Jan, 03 Feb, 10 Feb 2026  
- **Strike range:** ~24,900 – 26,500  
- **Price used:** Last Traded Price (LTP)  
- **Spot:** 25,694  
- **Risk-free rate:** 6.75% (continuous compounding, INR proxy)

---

## Methodology
- ACT/365 time-to-maturity calculation  
- Black–Scholes pricing for European index options  
- Numerical IV inversion using Brent’s method  
- Surface constructed in **Strike × Expiry × Implied Volatility**

---

## Outputs
- 3D implied volatility surface  
- Volatility smile slices across expiries  

---

## Limitations
- LTP used instead of bid-ask mid  
- No vega-based filtering or arbitrage constraints  
- No parametric smoothing (e.g., SVI / SABR)  
- Black–Scholes model limitations apply  

---

## Possible Extensions
- Mid-price IV extraction  
- Vega filtering and liquidity checks  
- Arbitrage-free surface fitting  
- Monthly and longer-dated expiries
