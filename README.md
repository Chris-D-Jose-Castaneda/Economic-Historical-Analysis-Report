# FRED Macro Dashboard and Regime Diagnostics

A compact macroeconomic dashboard built with Python and FRED data to analyze U.S. growth, inflation, labor, rates, volatility, and recession-sensitive signals. The project combines dashboard visualizations, regime analysis, lead-lag diagnostics, inflation persistence, and yield-curve risk signals.

## Scope

- Pulls macroeconomic series from FRED
- Cleans and reshapes data into analysis-ready panels
- Builds visual diagnostics for rates, CPI, unemployment, VIX, and the yield curve
- Evaluates hiking, hold, and cutting regimes
- Tests lead-lag relationships and recession-related signals
- Exports a consolidated Excel file for downstream use

## Files

- `Analysis.ipynb` — main notebook
- `Report.pdf` — written macro report
- `macro_data.xlsx` — excel data is saved after running the notebook. Unfortunately the file size exceed limit 
- `.gitignore` — excludes secrets and notebook checkpoint files

## Data sources

Primary data comes from Federal Reserve Economic Data (FRED), including GDP, CPI, unemployment, Fed funds, Treasury yields, VIX, and recession indicators.
