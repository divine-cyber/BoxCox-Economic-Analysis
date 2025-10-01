# BoxCox Economic Analysis

This repository contains an R Markdown file applying Box-Cox transformations to several economic time series datasets using the `fpp3` package in R.

## Project Goals

- Explore GDP per capita trends across countries.
- Identify countries with the highest GDP per capita.
- Analyze economic time series (GDP, livestock slaughter, electricity demand, gas production).
- Apply Box-Cox transformations to stabilize variance.
- Document when transformations are beneficial.
  
## Datasets Used

This project uses the following datasets from the **fpp3** package:

- **global_economy** — GDP and population data for over 200 countries.
- **aus_livestock** — Slaughter counts of livestock in Victoria, Australia.
- **vic_elec** — Half-hourly electricity demand for Victoria, Australia.
- **aus_production** — Monthly Australian gas production and other production series.
- **canadian_gas** — Monthly Canadian gas production.
- **ansett** — Passenger data between Melbourne and Sydney.
- **pedestrian** — Pedestrian counts at various stations in Melbourne.

These datasets allow for a broad examination of economic time series and their transformations.

---
## Files

- `BoxCox_Economic_Analysis.Rmd` — Main analysis file.

## Methodology

The analysis uses the `fpp3` R package to work with time series data. For GDP per capita, only the top 10 countries are plotted for clarity. Colors are automatically assigned to distinguish countries.

## Author

Divine Gatebuka
