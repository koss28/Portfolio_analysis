# Portfolio Analysis Project

## Overview

This project analyzes an actively managed equity portfolio.
The objective is to evaluate:

- portfolio performance;
- risk characteristics;
- diversification;
- sources of return;
- risk-adjusted performance;
- portfolio robustness under different market regimes.

---

## Portfolio Composition

Current allocation:

|Ticker|Weight|
|-|-:|
|S|30%|
|PFE|20%|
|OKTA|15%|
|PG|15%|
|KHC|10%|
|SIRI|5%|
|FUSD.L|5%|

Portfolio type:
Active equity portfolio.

Investment approach:
Sector and company-specific allocation with changing themes over time.

---

## Data

Period analyzed:

2022-02-01 — 2026-07-25

Benchmark:

- SPY (S&P 500 ETF)
- QQQ (Nasdaq 100 ETF)

Data source:

Yahoo Finance via yfinance.

---

## Research Progress

### Completed

[x] Return calculation  
[x] Annualized volatility  
[x] VaR / CVaR  
[x] Sharpe ratio  
[x] Sortino ratio  
[x] Maximum drawdown  
[x] Recovery analysis  
[x] Correlation analysis  
[x] PCA diversification analysis  
[x] Risk contribution  
[x] Benchmark comparison  
[x] Alpha / Beta analysis  
[x] Regime analysis  
[x] Return attribution  

### In Progress

[ ] Stress testing  
[ ] Monte Carlo simulation  
[ ] Factor exposure analysis  
[ ] Portfolio optimization  
[ ] Scenario analysis  

---

## Current Findings

### Overall period

The portfolio underperformed SPY over the full historical period.

Key metrics:

- Portfolio volatility: 26.59%
- SPY volatility: 17.29%
- Portfolio max drawdown: -39.31%
- SPY max drawdown: -22.09%

---

### Recent regime

Performance improved significantly after 2025.

2026 YTD:

Portfolio:
- Return: 36.81%
- Sharpe: 1.38
- Alpha vs SPY: +27.99%

Main contributors:
- OKTA
- S
- SIRI

Main risk contributor:
- S