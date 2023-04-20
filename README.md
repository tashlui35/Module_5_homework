# Module_5_homework

In this assignment, I created a personal financial planner for emergencies. 

In part 1, I determined the current value of a member’s cryptocurrency wallet by collecting the current prices for the Bitcoin and Ethereum cryptocurrencies by using the Python Requests library. I then determined the current value of a member’s stock and bond holdings by make an API call to Alpaca via the Alpaca SDK to get the current closing prices of the SPDR S&P 500 ETF Trust (ticker: SPY) and of the iShares Core US Aggregate Bond ETF (ticker: AGG).


After that I used the valuations for the cryptocurrency wallet and for the stock and bond portions of the portfolio to determine if the credit union member has enough savings to build an emergency fund into their financial plan by analysing savings health and comparing to a reasonable emergency fund.

In part 2, I used the Alpaca API to get historical closing prices for a retirement portfolio. I then ran Monte Carlo simulations to forecast the portfolio performance 30 years from now. I used the MCForecastTools library to create a Monte Carlo simulation for the member’s savings portfolio. Then I repeated this for 5 and 10 years respectively.
