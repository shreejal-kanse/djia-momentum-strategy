# DJIA Momentum Strategy Backtest

This project implements and backtests a 52-week high/low momentum trading strategy on the Dow Jones Industrial Average (DJIA) using Python.

## Strategy Overview
- Go long when price reaches a 52-week high
- Go short when price reaches a 52-week low
- Exit positions after a 5% adverse move or after 20 trading days
- Stay in cash when no active signals are present

## Data
- Daily price data for DJIA and its constituents
- Risk-free rate used during cash periods

## Methodology
- Rolling 52-week high/low signal generation
- Trade execution and position management logic
- Performance comparison against a buy-and-hold benchmark

## Performance Metrics
- Total return
- Annualized volatility
- Sharpe ratio
- Maximum drawdown

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib

## Key Takeaway
The strategy demonstrates how momentum signals can be systematically implemented and evaluated, with a focus on risk-adjusted performance.
