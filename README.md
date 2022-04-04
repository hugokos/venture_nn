# venture_nn
Neural network analyzing venture capital data

This Jupyter Notebook is a financial planning tool that uses APIs for portfolio analysis of crypto, stock, and bond allocations

---

## Technologies

Project uses:

[Pandas](https://pandas.pydata.org/)

[json](https://www.json.org/json-en.html)

[dotenv](https://www.npmjs.com/package/dotenv)

[alpaca_trade_api](https://pypi.org/project/alpaca-trade-api//)

[MCForecastTools](https://pypi.org/project/forecast-tools/)

---

## Installation Guide

Run this program in Jupyter notebook and have a API keys ready from Alpaca



---

## Usage

Utilize Jupyter Labs to interact with the software program

!["Jupyter Labs Example"](https://miro.medium.com/max/955/1*mXGu0MeYgnUkyR9ybVlQpg.png)

**Key example code for MonteCarlo Simulations**
```
# Configure the Monte Carlo simulation to forecast 30 years cumulative returns
# The weights should be split 40% to AGG and 60% to SPY.
# Run 500 samples.
mc_traditional = MCSimulation(
    portfolio_data = prices_df,
    weights = [.40,.60],
    num_simulation = 500,
    num_trading_days = 252*30
)

# Review the simulation input data
mc_traditional.portfolio_data.head()
```

---

## Contributors

Hugo Kostelni

---

## License

Open Source
