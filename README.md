# Risk Analysis and Forecasting of Tech Stocks

This project provides a comprehensive analysis of the "Magnificent 7" tech stocks: Apple (AAPL), Google (GOOG), Meta (META), Amazon (AMZN), Netflix (NFLX), NVIDIA (NVDA), and Tesla (TSLA). The analysis covers historical performance, risk-return profiles, portfolio optimization, and forecasting using Monte Carlo simulations.

## 🚀 Features

* **Historical Data Analysis**: Fetches and analyzes historical stock data, including closing prices, trading volume, and moving averages.
* **Risk and Return Analysis**: Evaluates the risk and return profiles of individual stocks and their correlations.
* **Monte Carlo Simulation**: Forecasts potential future stock performance and estimates Value at Risk (VaR).
* **Portfolio Optimization**: Implements Modern Portfolio Theory (MPT) to find the optimal portfolio allocation for maximizing risk-adjusted returns (Sharpe Ratio).
* **Backtesting**: Compares a monthly rebalancing strategy against a simple buy-and-hold strategy.

---

## 🛠️ Technologies Used

* **Python**: The core programming language used for the analysis.
* **Jupyter Notebook**: For interactive data analysis and visualization.
* **Pandas**: For data manipulation and analysis.
* **NumPy**: For numerical operations.
* **Matplotlib & Seaborn**: For data visualization.
* **yfinance**: For fetching historical stock market data from Yahoo Finance.
* **SciPy**: For statistical analysis.

---

## Project Structure

The project is divided into two main Jupyter Notebooks:

### 1. `Analyzing and Predicting Magnificent 7 Stocks.ipynb`

This notebook focuses on the analysis of individual stocks. It includes:
* **Exploratory Data Analysis (EDA)** of historical stock data.
* **Risk vs. Return analysis** for each of the Magnificent 7 stocks.
* A **Monte Carlo simulation** to forecast the potential risk of loss for Google (GOOG) stock.

### 2. `M7_optimization.ipynb`

This notebook builds upon the initial analysis to perform portfolio-level optimizations and risk assessments. It covers:
* **Portfolio optimization** using Modern Portfolio Theory to find the portfolio with the maximum Sharpe Ratio.
* **Value at Risk (VaR) simulation** to compare the risk of the optimal portfolio with an equally weighted portfolio.
* **Backtesting** of a monthly rebalancing strategy.

---

## Usage

1.  Launch Jupyter Notebook or JupyterLab.
2.  Open either of the `.ipynb` files to view and run the analysis.
3.  You can modify the stock tickers, date ranges, and simulation parameters within the notebooks to customize the analysis.

---

## Acknowledgments

* The historical stock data is sourced from Yahoo Finance.
