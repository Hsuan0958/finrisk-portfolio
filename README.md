# finrisk-portfolio

> **Samantha Chen** | UC Berkeley Master of Analytics '27 (IEOR)  
> Quantitative Risk Analytics Portfolio — Summer 2026  
> Python · Risk Modeling · Derivatives Pricing · VaR

---

## Overview

This portfolio documents hands-on implementations in financial derivatives pricing and quantitative risk analytics, built in preparation for **Summer 2027 Risk Analytics / Data Analytics internships**.

Three projects progress from foundational options theory to production-style risk dashboards:

| Project | Topic | Status |
|---------|-------|--------|
| [Project 0](./project0-payoff-diagrams/) | Options Payoff & Profit Diagrams | 🔨 In Progress |
| [Project 1](./project1-bsm-pricer/) | BSM Option Pricer + Implied Volatility Surface | 📋 Planned |
| [Project 2](./project2-risk-dashboard/) | Portfolio Risk Dashboard (VaR + Stress Testing) | 📋 Planned |

---

## Project 0 — Options Payoff & Profit Diagrams

**Goal:** Build interactive visualizations for the four basic option strategies, demonstrating understanding of payoff structures, breakeven analysis, and moneyness.

**Contents:**
- `payoff_diagrams.ipynb` — Core notebook with static plots
- `interactive_payoff.ipynb` — Jupyter widget version with live sliders

**Concepts covered:**
- Long/Short Call & Put payoff diagrams
- Profit diagrams (net of premium)
- Moneyness visualization (ITM / ATM / OTM)
- Breakeven price analysis

**Libraries:** `numpy`, `matplotlib`, `ipywidgets`

---

## Project 1 — BSM Option Pricer + Implied Volatility Surface

**Goal:** Implement Black-Scholes-Merton pricing from scratch, compute the four Greeks, and visualize the implied volatility surface using real market data.

**Contents:**
- `bsm_pricer.ipynb` — BSM formula implementation + Greeks
- `iv_surface.ipynb` — Implied volatility surface with `yfinance` data

**Concepts covered:**
- Black-Scholes-Merton closed-form solution
- Greeks: Delta, Gamma, Vega, Theta
- Implied volatility (numerical inversion via Newton-Raphson / Brent's method)
- IV surface visualization across strikes and maturities

**Libraries:** `numpy`, `scipy`, `matplotlib`, `yfinance`, `plotly`

---

## Project 2 — Portfolio Risk Dashboard

**Goal:** Build a multi-asset portfolio risk system with Historical VaR, Monte Carlo VaR, and 2008 Financial Crisis stress testing scenario.

**Contents:**
- `risk_dashboard.ipynb` — Main dashboard notebook
- `stress_test.ipynb` — 2008 crisis scenario analysis

**Concepts covered:**
- Historical Value-at-Risk (95% / 99% confidence)
- Monte Carlo VaR with correlated asset returns
- Stress Testing: 2008 GFC drawdown scenario
- Portfolio P&L attribution

**Libraries:** `numpy`, `pandas`, `scipy`, `matplotlib`, `yfinance`, `plotly`

---

## Technical Stack

```
Python 3.11+
numpy · pandas · scipy · matplotlib · plotly
yfinance · ipywidgets · jupyter
```

---

## Background

- **Education:** NCCU Statistics + Business Administration (GPA 3.99/4.3) → Berkeley MAnalytics '27
- **Relevant Experience:** Yuanta Securities (derivatives desk — GARCH pricing, risk reports); AstraZeneca (predictive modeling)
- **Visa:** F-1, CPT/OPT eligible — no sponsorship required

---

## Contact

📧 samantha07162002@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/samantha-chen) | UC Berkeley MAnalytics '27
