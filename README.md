<!-- This is an empty Markdown file -->

# Stock Market Quantitative Analysis using Python

This repository contains a quantitative analysis of the stock market performance of four major companies: Apple Inc. (AAPL), Alphabet Inc. (GOOG), Microsoft Corporation (MSFT), and Netflix, Inc. (NFLX). The analysis is performed using Python and various data analysis libraries.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis](#analysis)
- [Results](#results)
- [Visualization](#visualization)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Quantitative analysis plays a crucial role in understanding and evaluating the stock market performance of companies. By utilizing mathematical and statistical techniques, investors can gain insights into trends, volatility, correlations, and risk-return profiles of stocks. This project focuses on the analysis of four prominent companies: AAPL, GOOG, MSFT, and NFLX.

## Dataset

The dataset used for this analysis contains historical stock market data, including daily opening prices, closing prices, high and low prices, adjusted closing prices, and trading volumes for each company. The dataset is stored in the `stocks.csv` file.

## Requirements

To run the code in this repository, you need the following dependencies:

- Python 3.x
- Pandas
- Plotly
- Plotly Express

## Installation

1. Clone this repository to your local machine:

git clone https://github.com/your-username/Quantitative-Analysis-of-Stock-Market.git

2. Navigate to the project directory:

cd stock-market-analysis-python

3. Install the required dependencies using pip:

pip install pandas plotly plotly_express

## Usage

1. Ensure that the `stocks.csv` file is in the same directory as the Python script.

2. Run the Python script:

python stock_analysis.py

3. The script will perform the quantitative analysis and visualize the stock market performance.


## Analysis

The quantitative analysis includes the following aspects:

1. Descriptive Statistics: Calculating summary statistics for each stock.
2. Time Series Analysis: Examining trends and price levels over the observed period.
3. Volatility Analysis: Measuring the price fluctuations of each stock.
4. Correlation Analysis: Investigating the relationships between the stock prices.
5. Comparative Analysis: Comparing the performance of different stocks based on percentage changes.
6. Risk-Return Analysis: Evaluating the risk-return trade-off for each stock.


## Results

The analysis provides valuable insights into the stock market performance of AAPL, GOOG, MSFT, and NFLX. The key findings include:

- MSFT and AAPL demonstrated strong performance and favorable risk-return profiles.
- GOOG and NFLX showed less favorable results during the analyzed period.
- AAPL exhibited the lowest risk with a positive average daily return.
- MSFT had the highest positive percentage change in closing prices.
- NFLX showed the highest volatility and a negative average daily return.


## Visualization

The project includes visualizations of the stock market performance using Plotly library. The generated plots include:

- Time Series of Closing Prices
- Volatility of Closing Prices (Standard Deviation)
- Correlation Matrix of Closing Prices
- Percentage Change in Closing Prices
- Risk vs. Return Analysis


## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.


