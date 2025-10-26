# Stock Price Forecasting using Monte Carlo Simulation 

This project explores stock price forecasting through the Monte Carlo Simulation method. Its a probabilistic approach that models thousands of possible future outcomes rather than a single deterministic prediction.

Instead of using traditional machine learning algorithms, this method leverages random sampling and statistical modeling to reflect the uncertainty and volatility of financial markets as real markets rarely move in straight lines.

## Objective

- Forecast future stock prices using Monte Carlo Simulations.
- Capture the range of possible outcomes to understand risk and volatility.
- Compare simulated predictions with actual market performance.

 Why Monte Carlo (and not ML)?

Unlike machine learning models that rely heavily on past data patterns, Monte Carlo Simulation focuses on probabilistic modeling. It doesn’t assume that history repeats perfectly. Instead, it explores many potential futures by running thousands of random trials, making it ideal for forecasting in uncertain or chaotic markets.

## Methodology

Data Collection:

- Historical stock prices (AAPL used in this project).

- Parameter Estimation: Calculated daily returns, volatility, and drift.

- Simulation: Generated 100,000 random price paths over 100 future days.

- Visualization: Displayed simulated trajectories to understand the range of outcomes.

- Validation: Predicted price for Sept 29: $255.41
              Actual closing price: $253.81 

## Tools & Libraries

- Python 
- NumPy – Random number generation & math operations
- Pandas – Data manipulation
- Matplotlib / Seaborn – Visualization
- yfinance – Fetching stock data

## Key Results

Forecasted mean closing price: $255.41 USD

Actual market closing: $253.81 USD

Confidence intervals:

95% range → $168 – $372

98% range → wider risk spread

 Model captured realistic market uncertainty and produced a close-to-actual forecast, highlighting the strength of stochastic simulations.

## Learnings

Gained deeper understanding of stochastic processes and random walks in finance.

Practiced translating probabilistic models into actionable risk analysis insights.

Learned how simulation-based modeling complements traditional ML and quant finance methods.

## Future Improvements

Extend to multi-asset simulations for portfolio-level forecasting.

Integrate volatility clustering (e.g., GARCH models) for more realism.

Build an interactive dashboard for visualization.

💬 Author

👩‍💻 Shachi
A Computer Science student exploring Quantitative Finance, Machine Learning, and Data Science.
Fascinated by how randomness, probability, and code can model financial reality 
