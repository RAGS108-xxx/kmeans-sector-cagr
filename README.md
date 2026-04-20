# KMeans Sector CAGR Analysis - NIFTY IT

Quantitative sector analysis using KMeans clustering on 15 NIFTY IT stocks.

## What it does
- Downloads 5-minute intraday candles via yfinance
- Simulates 1 full year of price data by tiling 60-day window x6
- Computes CAGR, Sharpe ratio, volatility, momentum and max drawdown per stock
- Clusters stocks using KMeans (best of 5 runs)
- Identifies the sector outlier by centroid distance
- Generates trade signals for each stock
- Produces 3 charts and exports results to CSV

## Tech Stack
Python, yfinance, scikit-learn, pandas, numpy, matplotlib

## How to Run
Open KMEAN_SECTOR_CAGR.ipynb in Google Colab and run all cells.
