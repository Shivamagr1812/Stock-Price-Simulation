# Options Pricing with Binomial and Black-Scholes Models
This project demonstrates how to use binomial models and the Black-Scholes formula to price European-style options using Python. The code fetches historical stock prices using yfinance, calculates volatility and returns, and estimates the option price based on various mathematical models.

# Requirements
Install the required dependencies by running the following command:
- pip install yfinance numpy matplotlib pandas scipy

# Code Explanation
## fetch_historical_data()
- Downloads the closing prices of the specified stock from Yahoo Finance for a given date range.

## calculate_mu_sigma()
- Calculates the expected return (mu) and volatility (sigma) based on historical prices using daily log returns.

## binom_EU1()
- Implements the binomial model to price European-style options. The function recursively calculates the option's value using a multi-step tree.

## black_scholes_call()
- Calculates the Black-Scholes call option price using the closed-form formula for European options.

## plot_prices()
- Plots the historical stock prices using matplotlib.