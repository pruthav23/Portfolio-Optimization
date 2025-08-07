# 📈 Portfolio Optimization & Efficient Frontier Visualization

This project implements **Modern Portfolio Theory (MPT)** to simulate and analyze a set of investment portfolios using historical returns and risk measures. It calculates the **Sharpe Ratio** for each portfolio and visualizes the **Markowitz Bullet** along with the **Efficient Frontier**.

---
- **Modern Portfolio Theory (MPT)**: Framework for constructing an optimal portfolio by maximizing return for a given level of risk.
- **Sharpe Ratio**: Measure of risk-adjusted return, calculated as:  
  \[
  \text{Sharpe Ratio} = \frac{R_p - R_f}{\sigma_p}
  \]
- **Efficient Frontier**: Set of portfolios offering the **highest return** for a given level of **risk**.
---

## Features

- Generates a large number of **random portfolios** with varying asset weights.
- Computes:
  - Portfolio **expected return**
  - Portfolio **risk (standard deviation)**
  - **Sharpe Ratio** for each portfolio
- Identifies the **portfolio with the maximum Sharpe Ratio**
- Plots:
  - All portfolios (Markowitz Bullet)
  - **Efficient Frontier** (upper boundary of optimal portfolios)
  - Highlighted **maximum Sharpe Ratio portfolio**

---

## Requirements

- Python 3.x
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `yfinance`

Install with:

```bash
pip install numpy pandas matplotlib
