# PLTR quantitative research

A study of historical risk, simulated returns, and business performance around my PLTR purchase on February 1, 2024, at $16.11.

## Notebooks

| Notebook | Purpose |
| --- | --- |
| `01_data_collection.ipynb` | Collect prices and analyst events. |
| `02_exploratory_analysis.ipynb` | Analyze returns, correlation, beta, and drawdown. |
| `03_expected_returns.ipynb` | Simulate prices using GBM and historical bootstrap. |
| `04_volatility.ipynb` | Compare 20-day and 60-day rolling volatility. |
| `05_fundamental_analysis.ipynb` | Analyze revenue growth and operating profitability. |
| `06_ex_post_calibration.ipynb` | Compare forecasts with realized outcomes (in progress). |

## Data and setup

Place notebooks in `notebooks/` and CSVs in `data/`:
`pltr_prices.csv`, `market_prices.csv`, `analyst_events.csv`, and `fundamentals.csv`.
Prices and analyst events come from Yahoo Finance; fundamentals come from SEC filings.

Use Python 3.12 or later:

```bash
pip install numpy pandas yfinance plotly scipy requests jupyter
```

Provide the separately collected `fundamentals.csv`, then run the notebooks in order.