# Stock Market Analysis: Tesla, Ford & GM

A Python data analysis project comparing the historical stock performance of three
major automotive companies — Tesla (TSLA), Ford (F), and General Motors (GM) — from
2012 to 2017. The analysis explores price trends, trading activity, volatility, and
risk-return profiles using pandas, NumPy, and Matplotlib.

## Overview

This project takes raw historical stock data and turns it into a clear comparison of
how these three companies performed relative to one another — the kind of exploratory
analysis used to understand risk, volatility, and return before making investment or
portfolio decisions.

## Tools & Libraries

- **Python**
- **pandas** — data manipulation and time series handling
- **NumPy** — numerical operations
- **Matplotlib** — data visualization

## What the analysis covers

- **Price trends** — opening price comparison across all three stocks over time
- **Trading volume** — daily volume traded, and identifying peak trading days
- **Total traded value** — combining price and volume to measure dollar activity
- **Moving averages** — 50-day and 200-day moving averages to smooth trends
- **Daily returns** — percentage change day-over-day to measure volatility
- **Distribution analysis** — histograms, KDE plots, and box plots comparing return spreads
- **Correlation** — scatter matrix and scatter plots to examine relationships between stocks
- **Cumulative returns** — growth of a hypothetical $1 invested in each company

## Key findings

- **Tesla** delivered the highest cumulative return over the period, but also showed the
  widest daily return distribution — meaning the highest volatility and risk.
- **Ford** had the lowest cumulative return of the three.
- **Ford and GM** showed a visible correlation in their daily returns, consistent with
  being established companies in the same traditional automotive market — while Tesla
  traded more independently.

## What I practiced

This project was built to apply core financial data analysis skills in Python: loading
and cleaning time series data, engineering new columns, calculating returns and moving
averages, and using multiple visualization techniques to draw and communicate
conclusions from the data.

## How to run

1. Clone this repository
2. Ensure the stock CSV files (`Tesla_Stock.csv`, `Ford_Stock.csv`, `GM_Stock.csv`) are
   in the same directory as the notebook
3. Install requirements: `pip install pandas numpy matplotlib`
4. Open `Stock Analysis Project.ipynb` in Jupyter and run all cells

---

*Built while completing coursework in Python for financial analysis, as part of my
transition into finance and data analytics.*
