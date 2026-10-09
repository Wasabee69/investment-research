# Investment Research

Independent investment research conducted for FNK AS. This repository uses Python to study individual stocks, combining quantitative methods with fundamental analysis to examine risk, potential returns, and business performance.

## Research approach

- **Historical risk:** daily returns, market correlation, beta, and maximum drawdown.
- **Monte Carlo simulation:** generate possible price paths using Geometric Brownian Motion and compare their terminal-price distributions with realized outcomes.
- **Historical bootstrap:** simulate alternative paths by resampling past returns with replacement.
- **Volatility analysis:** examine rolling estimates and assess the fixed-volatility assumption used in GBM.
- **Fundamental analysis:** evaluate revenue growth, operating profitability, and financial information available at the investment date.

Historical forecast comparisons use information available before the forecast starts. Each study documents its assumptions and limitations; simulated outcomes depend on the model and data used.

## Repository contents

Each stock has its own ticker folder containing Jupyter notebooks, data snapshots, charts, and a project README. The notebooks cover data collection, exploratory analysis, simulations, fundamentals, and comparisons between expected and realized performance.
