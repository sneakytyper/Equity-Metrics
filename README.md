# 📈 EquityMetrics: Investment Analysis for Equity Portfolio

A Python-powered toolkit for fetching equity data, calculating risk/return metrics, and visualizing portfolio performance. Designed for quants, analysts, and investors.

---

## 🌟 Key Features

### 📊 Core Analytics
- **Returns Calculation**: Simple returns, log returns, cumulative returns
- **Risk Metrics**: 
  - Volatility (annualized std. dev.)
  - Value at Risk (VaR) - Historical & Parametric
  - Expected Shortfall (CVaR)
  - Maximum Drawdown (MDD)
- **Performance Ratios**:
  - Sharpe, Sortino, Treynor, Calmar
  - Alpha, Beta (CAPM)

### 🔧 Technical Implementation
- **Data Pipeline**: Automated Yahoo Finance API integration
- **Portfolio Optimization**: Efficient Frontier (Markowitz) support
- **Visualization**: Interactive plots with Matplotlib/Seaborn

---

## 🛠 Installation

### Prerequisites
- Python 3.8+
- pip package manager

### Quick Start
```bash
git clone https://github.com/sneakytyper/EquityMetrics.git
cd EquityMetrics
pip install -r requirements.txt
