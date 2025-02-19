# Project 1: Stock Price Spread Modeling and Simulation

## Overview
This project analyzes the spread between Coca-Cola (KO) and Pepsi (PEP) stock prices, using historical data and mean-reverting process simulations. The objective is to estimate potential profits and losses over time using Monte Carlo simulations.

## Features
- **Stock Price Data Processing:** Loads historical stock prices from a dataset.
- **Spread Calculation:** Computes price differences between KO and PEP stocks.
- **Mean-Reverting Process Simulation:** Uses the Ornstein-Uhlenbeck model to simulate future spread paths.
- **Monte Carlo Simulations:** Runs 1 million simulations to estimate expected profits and losses.
- **Risk Analysis:** Calculates expected values and percentiles of trade outcomes for January 31st and June 30th.

## Methodology
1. **Load and Filter Stock Price Data:**
   - Reads KO and PEP stock prices from a dataset.
   - Filters data to include records up to December 31, 2023.
   
2. **Compute Price Spread and Trend:**
   - Calculates the relative spread between KO and PEP stocks.
   - Identifies and adjusts for historical trends.
   
3. **Mean-Reverting Process Simulation:**
   - Uses the Ornstein-Uhlenbeck equation to model the spread’s reversion to its mean.
   - Incorporates stochastic noise using standard normal random variables.
   
4. **Monte Carlo Simulation:**
   - Generates 1 million future price paths.
   - Simulates profit and loss outcomes at different time points.
   
5. **Risk Analysis and Expected Returns:**
   - Computes expected profits and losses.
   - Analyzes 5th and 95th percentile risk levels.

## Results
- Provides estimates of expected returns and risk measures for trades on January 31st and June 30th.
- Demonstrates the impact of stock price correlation and mean-reverting tendencies on potential profit outcomes.
- Uses percentile analysis to assess worst-case and best-case scenarios.

## Dependencies
- MATLAB with Statistics and Machine Learning Toolbox.

## Usage
Run the provided MATLAB script to:
- Load and analyze stock price data.
- Simulate spread movements using Monte Carlo methods.
- Compute expected returns and risk measures.

## Author
Aviel Avshalumov

## License
This project is licensed under the MIT License.

