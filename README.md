# Historical Stock and Revenue Dashboard

A notebook-based analysis of Tesla and GameStop that combines historical share-price data with company revenue data and presents both series in interactive Plotly dashboards.

## Project overview

The notebook demonstrates an end-to-end financial-data workflow:

1. Retrieve historical stock prices with `yfinance`
2. Extract quarterly revenue data from public web pages
3. Clean dates, currency values, and missing records with Pandas
4. Visualize stock prices and revenue together using Plotly
5. Compare the market histories of Tesla (`TSLA`) and GameStop (`GME`)

## Technologies

Python, Jupyter Notebook, Pandas, yfinance, Requests, Beautiful Soup, and Plotly.

## Repository contents

```text
.
├── Final Assignment.ipynb
└── README.md
```

## Run locally

```bash
git clone https://github.com/sohanmirylkar/Analyzing_Historical_Stock_Revenue_Data_and_Building_a_Dashboard.git
cd Analyzing_Historical_Stock_Revenue_Data_and_Building_a_Dashboard
python -m venv .venv
python -m pip install jupyter pandas yfinance requests beautifulsoup4 plotly
jupyter notebook "Final Assignment.ipynb"
```

> Web-scraped tables can change over time. If a source page changes its markup, the extraction cells may require a selector update.

## Skills demonstrated

- Programmatic financial-data collection
- Web scraping and HTML-table parsing
- Data cleaning and time-series transformation
- Interactive visualization
- Reproducible analysis in Jupyter

## Context

Completed for the IBM *Python Project for Data Science* course.

## Author

Sohan Miryalkar
