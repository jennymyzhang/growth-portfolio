# Sprout

> Creates a high-growth portfolio for ambitious investors

<!-- Image goes here -->

## What is Sprout?

Sprout is a portfolio optimization algorithm that creates a **high-growth portfolio** to achieve a high level of expected return in the stock market.

It uses statistical analysis of stock data extracted from [yfinance]() and evaluates such data to produce an optimal portfolio allocation for growth.

This optimizer is primarily targeted towards financially ambitious clients.

### Vision (objective)

The objective of Sprout is to provide an opportunity for growth seeking investors to quantitatively achieve a high-growth portfolio allocation that maximizes the level of expected return for a given level of preferred risk. 

### Key Features

The core functionality of the algorithm analyzes market cap, beta, standard deviation, and expected return to evaluate the profitability of each individual stock in a list of given stock tickers.

The optimization is done through analysis of the Sharpe Ratio, which indicates the relative volatility, thus resulting in a portfolio allocation that grants investors the highest level of return for their highest tolerable level of risk.

In addition, a Command Line Interface was built for clients to customize and adjust the generated portfolio to the preferred level of risk tolerance.

This optimization algorithm has shown success in the real world, as it **outperformed the S&P 500 by 70%** in a 4-week testing period during January 2022.

### Status

Sprout has been in development since November 2021, with new features and iterations currently in progress.

### Tech Stack

Sprout is built with the Python language and uses various Python libraries to optimize its functionality.

**Libraries Used:** Yahoo Finance, Numpy, Pandas, Matplotlib

## License

This repository is licensed under copyright.

Copyright © 2022 jennymyzhang. All rights reserved.

