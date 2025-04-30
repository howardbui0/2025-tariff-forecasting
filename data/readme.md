# Data Folder

This folder contains the final dataset used in the analysis and simulations for the 2025 Tariff Forecasting project.

## `main.csv`

This file is a cleaned and consolidated dataset created from scratch by aggregating and processing trade and tariff data scraped from the World Bank’s WITS portal. It includes data on:

- Annual U.S. imports and exports (2000–2022)
- Trade values by country and product group
- Tariff rates and trade policy indicators (e.g., MFN and AHS metrics)
- Growth rates and comparative advantages for each trade partner

This dataset was used in all stages of the project, including exploratory data analysis, regression modeling, and time-series forecasting.

### Columns Include:
- `Year`
- `Country`
- `Product Group`
- `Import (US$ Billion)`
- `Export (US$ Billion)`
- `MFN MaxRate (%)`
- `MFN AVE Tariff Lines Share (%)`
- `AHS Simple Average (%)`
- `World Growth (%)`
- `Country Growth (%)`
- `Revealed comparative advantage`
- *(and other relevant features)*

## Reproducibility

The original data was collected using custom web scraping scripts (`notebooks/scraping/`) and preprocessed using pandas. If you'd like to reproduce or customize the dataset, refer to the notebooks provided in the repo under `/notebooks/`.

## File Format

- CSV file
- UTF-8 encoded
- Numeric columns have been converted to standardized formats (e.g., US$ Billion)

---
