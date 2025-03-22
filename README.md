
---

### **README for Modern Portfolio Theory (MPT)**
Save this as `README.md` in your Modern Portfolio Theory project folder.

```md
# Modern Portfolio Theory (MPT) Implementation

## Project Overview
This project applies Modern Portfolio Theory (MPT) to construct an optimal investment portfolio. It utilizes Python to fetch financial data and analyze asset returns to determine the best risk-adjusted portfolio allocation.

## Features
- Fetch stock price data using `yfinance`
- Calculate historical returns and risk metrics
- Implement portfolio optimization techniques
- Visualize the efficient frontier

## Installation
Ensure you have the following dependencies installed:
```sh
pip install numpy pandas matplotlib yfinance scipy
import yfinance as yf
import pandas as pd

# Define the list of tickers
tickers = ["AAPL", "MSFT", "GOOGL", "AMZN", "TSLA"]

# Download historical data
data = yf.download(tickers, start="2020-01-01", end="2023-01-01")

# Access the 'Close' prices
data = data['Close']

---

You can now upload these `README.md` files along with your notebooks to GitHub! 🚀 Let me know if you need any modifications.
# Portfolio-Optimisation
