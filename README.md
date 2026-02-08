# Portfolio Diversification and Risk–Return Analysis (Python)

## Overview
This project analyzes the diversification benefits and risk–return trade-offs of a multi-asset portfolio using daily data from **2016 to 2025**. The analysis applies modern portfolio theory to a set of traditional and alternative assets, combining financial intuition with data-driven methods implemented in Python.

---

## Asset Universe
The portfolio consists of five asset classes, represented by widely used financial proxies:

- **SPY** – US Equities (S&P 500)
- **VEA** – International Equities (Developed Markets ex-US)
- **IEF** – US Treasury Bonds (Intermediate Term)
- **GLD** – Gold
- **BTC** – Bitcoin

---

## Methodology
The analysis follows these main steps:

1. **Data Collection & Cleaning**
   - Daily adjusted price data downloaded from Yahoo Finance
   - Alignment of trading days across assets
   - Return computation using adjusted prices

2. **Risk and Diversification Analysis**
   - Annualized volatility estimation
   - Correlation analysis across asset classes

3. **Portfolio Construction**
   - Equal-weight portfolio as a baseline
   - Minimum volatility portfolio
   - Maximum Sharpe ratio portfolio
   - Optimization performed using *PyPortfolioOpt*

4. **Robustness Checks**
   - Re-estimation of optimized portfolios across subperiods (2016–2020, 2021–2025)
   - Comparison of portfolio weights to assess stability and estimation risk

---

## Key Findings
- Traditional diversification between equities and bonds remains effective.
- Gold displays sustained growth with volatility characteristics distinct from equities and bonds.
- Bitcoin exhibits substantially different growth dynamics and volatility relative to traditional assets.
- Optimized portfolios are sensitive to the estimation window, highlighting the importance of robustness checks in portfolio construction.

---

## Tools & Libraries
- Python  
- pandas, numpy  
- matplotlib, seaborn  
- yfinance  
- PyPortfolioOpt  
- scikit-learn  

---

## Project Structure

```
portfolio-diversification-project/
│
├── notebooks/
│   └── portfolio_diversification.ipynb
│
├── data/
│   └── (optional saved datasets)
│
└── README.md
```
---

## Author
**Saman Zare** 