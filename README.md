# Diesel Signal Dashboard

**Why your pump price doesn't match reality — and how to read the market correctly.**

A data intelligence dashboard built to explain the disconnect between 
NYMEX futures volatility and actual U.S. distillate supply fundamentals. 
Built by someone who spent 19 years in the cab before picking up a keyboard.

## Live Demo
[edkiiru.github.io/diesel-signal-dashboard](https://edkiiru.github.io/diesel-signal-dashboard)

## What It Shows
- U.S. distillate inventory vs. 5-year seasonal average (the real signal)
- ULSD futures spike vs. inventory-implied price floor (signal vs. noise)
- Full pricing cascade from OPEC headline to DOE retail benchmark
- Data methodology table with source priority, cadence, and direct links

## Data Sources
| Source | What It Provides | Cadence |
|--------|-----------------|---------|
| [EIA WPSR](https://www.eia.gov/petroleum/supply/weekly/) | Distillate stocks vs. 5-yr avg | Weekly Wed |
| [DOE Retail Diesel (GASDESW)](https://fred.stlouisfed.org/series/GASDESW) | Fuel surcharge benchmark | Weekly Tue |
| ULSD NYMEX HO Front Month | Wholesale direction confirmation | Daily |
| EIA Refinery Utilization | Supply vulnerability indicator | Weekly |
| [IEA Oil Market Report](https://www.iea.org/reports/oil-market-report) | Global reserves context | Monthly |

## Stack
Pure HTML · Chart.js · No frameworks · No build step · No backend

## Context
Built as part of a career transition from logistics (Bighorn Freight, 
Sacramento CA) into data analytics and business intelligence.
Domain expertise + analytical framework = the combination most 
data portfolios are missing.

## Author
Ed Kiiru · [LinkedIn](https://linkedin.com/in/YOURHANDLE)
