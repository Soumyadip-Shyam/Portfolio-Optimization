# NSE Nifty 50 Portfolio Optimization using Modern Portfolio Theory

## 📊 Project Overview

This project implements a comprehensive **data-driven stock portfolio optimization model** using Modern Portfolio Theory (MPT) specifically designed for the **Indian stock market (NSE)**. The system determines the most efficient allocation of capital across Nifty 50 companies to maximize risk-adjusted returns measured by the Sharpe Ratio[1].

## 🎯 Key Features

- **Real-time NSE Data Integration**: Automated extraction of historical stock data for all Nifty 50 companies using multiple data sources
- **Advanced Portfolio Optimization**: Implementation of mean-variance optimization with SLSQP algorithm for constrained optimization[2]
- **Monte Carlo Simulation**: Generation of 15,000+ random portfolios to visualize the efficient frontier
- **Multi-objective Optimization**: 
  - Maximum Sharpe Ratio optimization
  - Minimum Variance optimization
  - Risk-constrained optimization
- **Comprehensive Risk Analysis**: Correlation matrices, beta calculations, and diversification metrics
- **Professional Visualizations**: Interactive plots showing efficient frontier, portfolio allocations, and risk-return profiles
- **Automated Reporting**: Export results to multiple CSV files and Excel workbooks

## 🚀 Technical Implementation

### **Core Algorithms**
- **Optimization Engine**: Sequential Least Squares Programming (SLSQP) for constrained optimization
- **Risk Modeling**: Covariance matrix calculations with annualized volatility measures
- **Performance Metrics**: Sharpe ratio, Treynor ratio, and risk-adjusted return calculations
- **Efficient Frontier**: Quadratic programming for optimal risk-return combinations

## 📚 Research & Methodology

- **Data Period**: 4+ years of historical data (2020-2024)
- **Frequency**: Daily price data with 252 trading days annualization
- **Risk Model**: Full covariance matrix with correlation analysis
- **Constraints**: Long-only portfolio with concentration limits
- **Validation**: Monte Carlo simulation with 15,000+ scenarios

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests for:
- Additional optimization algorithms (Black-Litterman, Risk Parity)
- Enhanced data sources and real-time feeds
- Advanced risk models (GARCH, Factor models)
- Machine learning integration
- Performance attribution analysis

## 🏷️ Tags

`#PortfolioOptimization` `#ModernPortfolioTheory` `#NSEIndia` `#QuantitativeFinance` `#Python` `#AlgorithmicTrading` `#RiskManagement` `#DataScience` `#FinTech` `#InvestmentStrategy`
