# Simple Moving Average Strategy

This project contains a basic implementation of a trading strategy based on the crossover of two simple moving averages (SMAs): 10 and 20 days.

## Description

The strategy generates buy signals when the 10-day SMA crosses above the 20-day SMA, and sell signals when it crosses below.

The code is designed to be used with the [backtesting.py](https://github.com/kernc/backtesting.py) library for performing historical backtests.

## Use

1. Install dependencies:

```bash
pip install backtesting
