# Pairs Trading Strategy

## Overview

This project implements a Pairs Trading strategy using statistical techniques to identify and exploit the relative price movements of two correlated assets. The strategy involves identifying pairs of assets that move together over time, and then trading on the divergence between their prices.

## Features

- **Stationarity Testing**: Utilized the Augmented Dickey-Fuller (ADF) test to ensure the time series data of selected assets are stationary, which is critical for reliable prediction.
- **Cointegration Analysis**: Conducted cointegration tests to identify pairs of assets that have a long-term equilibrium relationship, providing potential trading opportunities when their prices diverge.
- **Feature Engineering**: Applied advanced feature engineering to optimize the trading signals, refining the key feature that captures the divergence between the asset pairs, enhancing the profitability of the strategy.

## Libraries and Tools

- **Python**: The core programming language used.
- **Numpy**: For numerical computations.
- **Pandas**: For data manipulation and analysis.
- **Statsmodels**: For statistical tests and models.
- **yfinance**: For fetching historical financial data.

## Getting Started

### Prerequisites

Ensure you have Python installed along with the following libraries:

```bash
pip install numpy pandas statsmodels yfinance
