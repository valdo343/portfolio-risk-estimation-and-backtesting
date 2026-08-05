# Portfolio Risk Estimation and Backtesting

An end-to-end quantitative finance project that implements and compares multiple portfolio risk estimation methodologies using Python.

The project estimates **Value-at-Risk (VaR)** and **Expected Shortfall (ES)** under different modeling assumptions and evaluates their predictive performance through rolling-window backtesting and statistical validation.

---

## Project Overview

This project implements three widely used approaches for market risk estimation:

- Historical Simulation
- Parametric (Variance-Covariance) VaR
- Monte Carlo Simulation

Beyond computing risk measures, the notebook evaluates model performance through out-of-sample backtesting and the Kupiec Proportion of Failures Test.

---

## Features

- Historical market data download with **yfinance**
- Portfolio construction using **fixed asset weights**
- Historical Value-at-Risk and Expected Shortfall
- Parametric VaR and ES
- Monte Carlo VaR and ES
- Rolling-window backtesting
- Kupiec Proportion of Failures Test
- Data visualization and model comparison

---

## Repository Structure

```

portfolio-risk-estimation-and-backtesting/
│
├── portfolio_risk_analysis.ipynb
├── requirements.txt
└── README.md

```

---

## Methods Implemented

### Historical Simulation

Non-parametric estimation based directly on historical portfolio returns.

### Parametric Method

Variance-Covariance approach assuming normally distributed returns.

### Monte Carlo Simulation

Risk estimation using simulated future market scenarios generated from the estimated covariance matrix.

### Backtesting

Rolling estimation window with VaR exception analysis.

### Statistical Validation

Kupiec Proportion of Failures Test.

---

## Technologies

- Python
- NumPy
- pandas
- SciPy
- Matplotlib
- Seaborn
- yfinance

---

## Author

**Oswaldo Bueno Rivera**

M.Sc. Candidate in Probability and Statistics

Interested in Quantitative Risk, Financial Modeling and Data Science.
