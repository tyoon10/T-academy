# Data Analysis and Visualization with Python

A complete intro course covering the Python data stack — from pandas fundamentals to interactive Plotly charts.

Originally developed as seminar materials for the [T academy](https://tacademy.skplanet.com/) Talk ON series.

## Notebooks

| # | Notebook | Topic |
|---|----------|-------|
| 01 | `01-jupyter-intro.ipynb` | Getting started with Jupyter Notebook |
| 02 | `02-pandas-fundamentals.ipynb` | pandas Series, DataFrame, indexing, groupby |
| 03 | `03-pandas-operations.ipynb` | Merge, concat, pivot tables, file I/O |
| 04 | `04-matplotlib.ipynb` | Line plots, subplots, styling, saving figures |
| 05 | `05-seaborn.ipynb` | Statistical visualization — distributions, categoricals, heatmaps, regression |
| 06 | `06-plotly.ipynb` | Interactive charts with Plotly Express and financial charts with yfinance |
| 07 | `07-monty-hall.ipynb` | Applied: simulating the Monty Hall problem |
| 08 | `08-capstone-housing.ipynb` | Applied: exploratory analysis of California housing prices |

## Data

Sample datasets are in `data/`:
- `gapminder.csv` — country-level life expectancy, GDP, and population (Gapminder)
- `Excel_Sample.xlsx` — sample spreadsheet for pandas I/O exercises

Notebooks 05-08 also use built-in datasets from seaborn and Plotly (tips, iris, gapminder, California housing).

## Requirements

- Python 3.6+
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn, plotly, yfinance

```bash
pip install pandas numpy matplotlib seaborn plotly yfinance jupyter
```

## License

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
