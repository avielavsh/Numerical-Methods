# Project 2: Credit Risk Modeling with Copulas

## Overview
This project models credit risk using bond rating transitions and copula-based simulations. The primary objective is to evaluate Value at Risk (VaR) and expected credit losses for a bond portfolio under different correlation structures.

## Features
- **Bond Ratings and Transition Probabilities:** Utilizes predefined credit rating probabilities to model bond default risks.
- **Monte Carlo Simulation:** Simulates bond transitions using Gaussian and multivariate copulas.
- **Portfolio Value and Risk Metrics:** Computes expected losses and 99% Value at Risk (VaR) for different bond portfolios.
- **Visualization:** Generates scatter plots and histograms to analyze risk distributions.

## Methodology
1. **Define Bond Ratings and Probabilities:**
   - Establishes transition probabilities for different credit ratings.
   - Uses normal inverse transformation to define Z-score boundaries for transitions.
   
2. **Generate Copula Samples:**
   - Creates correlated samples using Gaussian and multivariate copulas.
   - Transforms uniform distributions to standard normal distributions.
   
3. **Monte Carlo Simulation:**
   - Simulates bond value transitions based on assigned probabilities.
   - Computes portfolio-level profit and loss (PnL).
   
4. **Risk Analysis:**
   - Calculates 99% VaR for different portfolio sizes.
   - Analyzes the impact of bond count on risk measures.

## Results
- The project estimates credit risk metrics for different correlation structures.
- The impact of correlation on portfolio losses is visualized through scatter plots and histograms.
- A comparison of Gaussian and multivariate models is conducted to assess risk exposure.

## Dependencies
- MATLAB with Statistics and Machine Learning Toolbox.

## Usage
Run the provided MATLAB script to:
- Generate credit transition simulations.
- Compute portfolio risk metrics.
- Visualize the impact of correlation on risk.

## Author
Aviel Avshalumov

## License
This project is licensed under the MIT License.

