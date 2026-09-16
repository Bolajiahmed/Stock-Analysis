Stock Analysis in Python
A Python project for downloading stock data, merging multiple tickers, computing statistical metrics, and visualizing investment growth over time.

This project uses yfinance, pandas, numpy, and matplotlib to perform multi‑stock analysis including:

Price normalization

Multi‑asset return comparison

Mean, standard deviation, and covariance calculations

Portfolio growth visualization
The function merge_stock() downloads historical data for any number of tickers and merges them into a single DataFrame.

✔ Normalize prices for comparison
plot_return_mul_stock() converts raw prices into investment‑growth curves:

value(𝑡)=price(𝑡)price(0)×investment
✔ Compute statistics
get_multi_mean_std() calculates:

Mean price

Standard deviation

Covariance

Code
AAPL has mean=151.67, std=12.62, covariance=0.0832
NFLX has mean=28.46, std=9.45, covariance=0.3321
GOOG has mean=114.11, std=15.86, covariance=0.1390

AMZN has mean=126.09, std=23.90, covariance=0.1895
✔ Plot multi‑stock returns
Visualizes how a fixed investment (e.g., £100) grows for each ticker over the selected period.
