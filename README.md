# Portfolio Analysis Project

## Group Members
- Saanavi Goyal
- Vanessa Campos
- Jannat Nabonee

## Project Overview
This project aims to analyze a portfolio of seven NYSE-traded stocks against major benchmarks, including the S&P 500 (SPY), Russell 2000 (IWM), and the Dow Jones Industrial Average (DIA). The analysis covers historical price data, risk assessment metrics, and performance comparisons.

## Objective
The primary objective is to conduct a comprehensive risk analysis of a selected stock portfolio and compare its performance against key market indices.

## Selected NYSE Traded Assets
1. Johnson & Johnson (JNJ)
2. Coca-Cola (KO)
3. The Walt Disney Company (DIS)
4. AT&T (T)
5. Boeing (BA)
6. CVS Health Corporation (CVS)
7. United Parcel Service (UPS)

## Key Steps
1. **Data Retrieval**: Use the Yahoo Finance API to gather historical price data for the selected stocks and benchmarks for the past 10 years.
2. **Volatility Calculation**: Calculate annualized volatility over the trailing three months and beta values against the benchmarks.
3. **Drawdown Analysis**: Determine average and maximum weekly drawdowns.
4. **Return Calculation**: Compute total and annualized returns over 10 years.
5. **Risk Analysis**: Create a risk analysis table summarizing the following metrics:
    - Ticker symbol
    - Portfolio weight (equally weighted)
    - Annualized volatility
    - Beta values against SPY, IWM, and DIA
    - Average and maximum weekly drawdown
    - Total return and annualized total return
6. **Portfolio Risk Evaluation**: Compare portfolio risk against selected ETFs, including:
    - Correlation and covariance with ETF returns
    - Standard deviation of ETF returns
    - Sharpe ratio calculations
    - Annualized volatility spread
7. **Correlation Matrix**: Generate and visualize a correlation matrix between the stock portfolio and ETFs.

## Installation
To run this project, ensure you have Python installed along with the following libraries:
- `yfinance`
- `pandas`
- `matplotlib`
- `numpy`
- `seaborn`

You can install the necessary libraries using pip:
```bash
pip install yfinance pandas matplotlib numpy seaborn
