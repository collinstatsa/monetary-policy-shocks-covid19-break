# monetary-policy-shocks-covid19-break
Monetary-policy shocks using VAR, local projections, and COVID-19 robustness checks.
# Monetary Policy Shocks and the COVID-19 Structural Break

## Overview

This project examines how inflation, industrial production, unemployment,
and the federal funds rate respond to monetary-policy shocks. It compares
vector autoregression and local-projection estimates and evaluates their
robustness to the COVID-19 structural break.

## Data

The analysis uses monthly observations from January 1990 to December 2023
retrieved automatically from the Federal Reserve Economic Data database.

FRED series:

- CPIAUCSL: Consumer Price Index
- INDPRO: Industrial Production Index
- UNRATE: Unemployment Rate
- FEDFUNDS: Federal Funds Effective Rate

## Methods

- Data transformation and visualization
- Vector autoregression with two lags
- Cholesky-identified impulse-response functions
- Local projections
- COVID-19 pulse indicators for March-May 2020
- Model comparison and robustness analysis

## Requirements

Install the required Python packages:

```bash
pip install -r requirements.txt
