
# 2025 Tariff Forecasting

This project analyzes and forecasts the economic implications of proposed 2025 U.S. tariffs using historical trade data and statistical modeling techniques. We investigate how different tariff scenarios, including retaliatory tariffs, could impact U.S. trade balances—particularly with top trade partners such as China, Mexico, Canada, Japan, and Germany.

## Overview

- Time Period Covered: 2000–2022
- Trade Data Source: World Bank WITS portal
- Final Dataset: See `/data/main.csv`
- Methods Used:
  - Web scraping with BeautifulSoup & Requests
  - Exploratory Data Analysis (EDA)
  - Ordinary Least Squares (OLS) Regression
  - Time-Series Forecasting
  - Polynomial Regression
  - Simulation of retaliatory tariffs
- For a full summary of methods, analysis, and conclusions, see the [final report (PDF)](report.pdf).


## Project Structure

```
2025-tariff-forecasting
├── data/
│   ├── main.csv                # Final cleaned dataset
│   └── README.md               # Dataset explanation
├── Report.pdf                  # Final notebook summarizing anaylsis
├── Data_Collection.ipynb       # Web scraping scripts and data wrangling
├── EDA_TradePartners.ipynb     # EDA identifying key trade partners and trends
├── EDA_TariffAnalysis.ipynb    # Deeper look at tariff effects by country and product
├── Simulation.ipynb            # Time-series & polynomial regression models
├── Report.ipynb                # Final notebook summarizing analysis
├── requirements.txt            # Project dependencies
└── .gitignore                  # Ignored files and folders
```

## Key Findings

- Imports from China and Mexico are likely to remain steady due to high dependency despite tariffs.
- Exports are expected to decline significantly under retaliatory tariff scenarios.
- Tariff policies may unintentionally deepen the trade deficit and increase consumer prices.

## Requirements

Install dependencies with:
```
pip install -r requirements.txt
```

Run notebooks in order:
1. Data_Collection.ipynb
2. EDA_TradePartners.ipynb
3. EDA_TariffAnalysis.ipynb
4. Simulation.ipynb
5. Report.ipynb

## Authors

- Aadhil Mubarak Syed – amubaraksyed@ucdavis.edu
- Siraj Zahid – sizahid@ucdavis.edu
- Howard Bui – howbui@ucdavis.edu

## License

This repository is intended for educational use. Contact the authors for reuse beyond academic purposes.
