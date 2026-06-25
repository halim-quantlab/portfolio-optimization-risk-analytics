# 📈 Portfolio Optimization and Risk Analytics

A modular Python framework for portfolio construction, optimization, performance attribution, and risk analysis using **Modern Portfolio Theory (MPT)**.

This project implements an end-to-end quantitative portfolio analytics workflow that enables investors to evaluate individual assets, construct optimized portfolios, analyze portfolio performance, and visualize risk metrics through interactive and reusable analytical modules.

---

## 🚀 Project Overview

This project provides a complete workflow for portfolio analytics, including:

- Downloading historical market data from Yahoo Finance
- Portfolio optimization using Monte Carlo simulation
- Construction of Maximum Sharpe, Minimum Volatility, and Equal Weight portfolios
- Portfolio performance evaluation
- Risk analysis and visualization
- CAPM performance attribution
- Rolling performance monitoring
- Portfolio comparison against multiple benchmark indices

The notebook is designed with a modular architecture, making it easy to extend with additional quantitative models in future development phases.

---

# ✨ Key Features

## Portfolio Construction

- Monte Carlo portfolio simulation
- Maximum Sharpe Portfolio optimization
- Minimum Volatility Portfolio optimization
- Equal Weight Portfolio benchmark
- Portfolio allocation visualization

---

## Performance Analytics

- Annualized Return
- Annualized Volatility
- Sharpe Ratio
- Portfolio ranking
- Combined Portfolio & Benchmark summary table

---

## Risk Analytics

- Historical Value at Risk (VaR)
- Conditional Value at Risk (CVaR / Expected Shortfall)
- Maximum Drawdown
- Rolling Drawdown
- Rolling Volatility

---

## CAPM Analysis

- Alpha
- Annualized Alpha
- Beta
- Rolling Beta
- R²
- Residual Volatility
- Portfolio CAPM Summary
- Ticker CAPM Summary

---

## Rolling Performance Analysis

- Rolling Return
- Rolling Volatility
- Rolling Sharpe Ratio
- Rolling Beta

---

## Correlation Analysis

- Correlation Matrix
- Covariance Matrix
- Correlation Heatmap
- Highest Correlation Pair
- Lowest Correlation Pair
- Best Diversifier Identification

---

## Visualization

- Monte Carlo Efficient Frontier
- Portfolio Allocation Pie Charts
- Portfolio Growth Comparison
- Portfolio Drawdown Comparison
- Rolling Performance Charts
- Rolling Beta Charts
- Correlation Heatmap

---

## Export Utilities

Automatically exports:

- CSV summary tables
- Excel summary tables
- High-resolution PNG figures

---

## Robust User Input Handling

The notebook automatically handles:

- Duplicate portfolio tickers
- Duplicate benchmark tickers
- Invalid ticker symbols
- Missing market data
- Invalid rolling window inputs
- Invalid benchmark selections

---

# 📂 Project Structure

```
Portfolio-Optimization-and-Risk-Analytics/
│
├── PortfolioOptimizationProject.ipynb
├── README.md
├── requirements.txt
│
├── data/
│   ├── Portfolio Summary
│   ├── CAPM Summary
│   ├── Rolling Metrics
│   ├── Drawdown Summary
│   ├── VaR & CVaR
│   └── Correlation Results
│
└── plots/
    ├── Efficient Frontier
    ├── Portfolio Allocation
    ├── Portfolio Growth
    ├── Drawdown
    ├── Rolling Metrics
    ├── Rolling Beta
    └── Correlation Heatmap
```

---

# 🛠 Technologies

- Python
- NumPy
- pandas
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- yfinance
- Jupyter Notebook

---

# 📊 Workflow

```
User Input
      │
      ▼
Historical Market Data
      │
      ▼
Return Calculation
      │
      ▼
Monte Carlo Portfolio Simulation
      │
      ▼
Portfolio Optimization
      │
      ▼
Performance Analytics
      │
      ▼
Risk Analytics
      │
      ▼
CAPM Analysis
      │
      ▼
Rolling Analytics
      │
      ▼
Visualization
      │
      ▼
Export Results
```

---

# 📈 Example Outputs

The project generates:

- Monte Carlo Efficient Frontier
- Portfolio Allocation Charts
- Portfolio Growth Comparison
- Portfolio Drawdown Comparison
- Rolling Performance Charts
- Rolling Beta Charts
- Correlation Heatmap
- Portfolio Summary Tables
- CAPM Summary Tables
- Risk Summary Tables

---

# 🗺 Roadmap

## ✅ Phase 1 — Portfolio Analytics Framework

- Portfolio optimization
- Risk analytics
- CAPM analysis
- Rolling analytics
- Correlation analysis
- Visualization
- Automated reporting

---

## 🚧 Phase 2 — Advanced Portfolio Construction

- Black-Litterman Model
- Risk Parity Portfolio
- Hierarchical Risk Parity
- Efficient Frontier Optimization
- Portfolio Rebalancing Strategies

---

## 🚧 Phase 3 — Quantitative Research

- Fama-French Factor Models
- Momentum Factor
- Quality Factor
- Factor Attribution
- Performance Attribution
- Regime Detection

---

## 🚧 Phase 4 — Professional Quant Research Toolkit

- Backtesting Engine
- Transaction Cost Modeling
- Portfolio Constraints
- Walk-Forward Validation
- Portfolio Dashboard (Streamlit)
- Interactive Reporting

---

# 🎯 Learning Objectives

This project demonstrates practical implementation of:

- Modern Portfolio Theory
- Portfolio Optimization
- Risk Management
- CAPM
- Quantitative Performance Evaluation
- Financial Data Analysis
- Python Software Engineering
- Data Visualization

---

# 👨‍💻 Author

**Wielly**

Product Engineer → Aspiring Quantitative Analyst

Incoming Master of Quantitative Finance (NUS)

---

## ⭐ Future Development

This repository is actively being expanded into a complete quantitative portfolio research framework throughout the NUS MQF program.

Contributions, feedback, and suggestions are always welcome.# portfolio-optimization-risk-analytics
