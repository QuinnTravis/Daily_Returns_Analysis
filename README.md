# Risk & Volatility Analysis of S&P 500 Stocks

This project analyzes the **daily returns, volatility, and risk-adjusted performance (Sharpe ratio)** of S&P 500 stocks over the past 5 years. It demonstrates quantitative finance concepts using Python and real market data.

## Dataset
- Source: `all_stocks_5yr.csv`  
- Columns: `date, open, high, low, close, volume, name`  
- Contains 5 years of daily stock prices for multiple S&P 500 companies.

## Project Goals
1. Calculate **daily returns** for each stock using a custom Python function.
2. Compute **annualized volatility** and **Sharpe ratio** for each stock.
3. Visualize the **distribution of daily returns** using histograms.

## Key Features
- Custom `daily_returns` function for numeric computation.
- Handles multiple stocks via grouping by `name`.
- Produces histograms for easy visualization of return distributions.
- Calculates risk metrics relevant for quantitative finance and portfolio analysis.

## Libraries Used
- `pandas` for data manipulation
- `numpy` for numerical operations
- `matplotlib` for plotting histograms



