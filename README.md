## API-Homework

Brief Summary of the Activity

The activity involved the use of all the skills learnt so far in the course of the bootcamp, while focusing on API as part of the technical solution, to create a financial analysis tool.

The first part of the activity which is tagged “Personal Finance Planning” which wanted a personal finance prototype to be developed.

Before beginning the task in this activity, the various libraries needed to complete the assignment was imported and installed

The savings portfolio given was made up of two crypto assets (BTC and ETH), 1 stock (SPY) and 1 bond (AGG)

Using the request library, the crypto prices were collected and the current value of 1.2 BTC and 5.3 ETH was derived as $89873.89 and $12363.58 respectively.

To collect the information needed for investments (SPY and AGG), Alpaca API was used to create an object. A timeframe was also set to generate the closing price and current value of 50 SPY and 200 AGG which stood at $19704.50 and $22758.00 respectively.

An analysis to assess the financial health was carried out and knowledge on the use of DataFrame was tested. A savings dataframe was created and the results showed the portfolio as a table with row and columns comprising crypto asset and shares with their values. A pie chart was also created for easy visuals.

An “if” conditional statements was used to validate if the current savings are enough for an emergency fund. The result showed that there was enough money for the fund.

The second part of the activity was tagged “Retirement Planning” which involved the use of Alpaca API to fetch historical closing prices for a retirement portfolio (SPY and AGG) and then use the MCForecastTools toolkit to create Monte Carlo simulations of 500 runs to project the portfolio performance at 30 years.

The simulation outcome, probability distribution and confidence interval was plotted accordingly. The summary statistics from the Monte Carlo simulation results was gotten and used to calculate the expected portfolio return in dollars at the 95% lower and upper confidence intervals given an initial investment of $20000 and $30000 respectively.

The results showed the following:

There is a 95% chance that an initial investment of $20000 in the portfolio over the next 30 years will end within in the range of $44332.52 and $274375.75


There is a 95% chance that an initial investment of $30000.0 in the portfolio over the next 30 years will end within in the range of $66498.77 and $411563.63
