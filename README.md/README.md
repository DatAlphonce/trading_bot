# Binance Testnet Trading Bot

A beginner project: a simple threshold-based trading bot for BTC/USDT, built in a Jupyter notebook using the Binance Spot Testnet.

## How it works
- Polls the BTCUSDT price every 3 seconds
- Buys 0.001 BTC when the price drops below a buy threshold
- Sells when the price rises above a sell threshold
- Tracks whether it is currently in a position

## Tech
Python, python-binance, python-dotenv, Jupyter

## Setup
1. Clone the repo and install dependencies:
   pip install -r requirements.txt
2. Create a Binance Spot Testnet account and generate API keys.
3. Copy `.env.example` to `.env` and add your testnet keys.
4. Open `trading_bot.ipynb` and run the cells in order.

## Notes
- Runs on testnet only. API keys are loaded from environment variables and never committed.
- Thresholds and quantity are set in the notebook and can be edited.

## Possible next steps
Stop-loss, error handling, logging, backtesting on historical data.

## Disclaimer
Educational project, not financial advice.