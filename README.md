# financial_planner
This program creates two financial planning toools by using a single Jupyter Notebook.

Part 1: A financial planner for emergiencies.  The members will b e able to use this tool to visualize their current savings.  The members can then determine if they have enough reservfes for an emergency fund.

Part 2 : A financial planner for retirement.  This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations


---

## Technologies
**Python 3.9** was used to code this app.  
Libraries used are **os, requrests, json, pandas, dotenv, alpaca_trade_api, MCForecastTools, and matplotlib**.

---

## Installation Guide
Make sure MCForecastTools.py is in the same folder as financial_planning_tools.ipynb.  
create a .env file with your alpaca api and secret keys.
Open financial_planning_tools.ipynb in Jupyter Lab.

---

## Usage
After running the app Jupyter Lab, feel free to update numbers held in the following variables to reflect your financial situation:
btc_coins
eth_coins
monthly_income
spy_shares
agg_shares
num_years

additionally, adjust weights for the monte carlo simulation to fit your risk appetite by adjusting the weights variable in the MC_thirty_years function.
---

## Contributors
This was created by Cuong Ha

---

## License
public
