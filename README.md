# Dynamic Systemic Risk & Spillover Analysis

## Overview
This project analyzes dynamic systemic risk transmission across global financial markets using econometric models including GARCH, VAR, and Diebold-Yilmaz spillover framework.

## Methodology
- GARCH(1,1) for volatility estimation
- VAR model for interdependence
- FEVD-based spillover index
- Markov regime switching for crisis detection

## Data
Daily financial data (2012–2024) from Yahoo Finance:
- Oil (BZ=F)
- Gold (GC=F)
- S&P500
- EUR/USD

## Results
- Spillover index time series
- Regime classification (crisis vs calm)
- Dynamic systemic risk visualization

## How to Run
```bash
pip install -r requirements.txt
python src/main.py

