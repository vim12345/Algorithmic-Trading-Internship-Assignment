# Project Overview

This project performs stock data analysis for five Nifty 50 stocks over the last six months using the yfinance library. It includes the calculation of daily percentage changes, moving averages, and the development and backtesting of a Moving Average Crossover strategy. Additionally, the project implements risk management techniques such as maximum drawdown calculation and stop-loss mechanisms.

# Features
Fetch historical stock data for five Nifty 50 stocks using yfinance.
Calculate and plot daily percentage changes and 20-day moving averages.
Develop and backtest a 50-day/200-day Moving Average Crossover strategy.
Compare strategy performance to a Buy-and-Hold approach.
Calculate maximum drawdown for risk analysis.
Implement a stop-loss mechanism with a comparison of performance.

# Requirements
Python 3.11
Required libraries:
yfinance
matplotlib
pandas
seaborn (optional for enhanced plotting)

# Instructions
# Task 1: Stock Data Analysis
Fetch Stock Data: Fetch historical stock data for five Nifty 50 stocks (RELIANCE.NS, TCS.NS, INFY.NS, HDFCBANK.NS, ITC.NS) from the past six months using yfinance.

Daily Percentage Change: Calculate the daily percentage change in stock prices for each stock.

Plot Closing Prices and Daily Percentage Changes: Plot the closing prices and daily percentage changes for the five stocks.

20-day Moving Average: Calculate the 20-day moving average for each stock and plot it alongside the closing prices.

# Task 2: Strategy Development
Moving Average Crossover Strategy: Implement a simple moving average crossover strategy using a short-term 50-day moving average and a long-term 200-day moving average.

Backtesting: Backtest the strategy to identify buy and sell signals and compare the returns with a Buy-and-Hold strategy.

Return Comparison: Calculate and compare the strategy's returns with a Buy-and-Hold approach.

# Task 3: Risk Management
Maximum Drawdown: Calculate the maximum drawdown for each stock during the six-month period.

Stop-Loss Mechanism: Implement a stop-loss mechanism (5%) for the selected stock and compare the performance with the original strategy.

# Results
The project generates:

Closing price and daily percentage change plots.
20-day moving average plots.
Buy/Sell signals for the moving average crossover strategy.
Strategy performance comparison with a Buy-and-Hold approach.
Maximum drawdown calculations.
Performance of the stop-loss mechanism.
