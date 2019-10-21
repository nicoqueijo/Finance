### M1 Finance Rebalancing Calculator/Simulator

M1 Finance is an investing platform which allows users to invest using fractional shares and custom weighting.

I've created a spreadsheet which simulates how a given portfolio would've performed in previous years using the M1 Finance investing platform. Given a list of stocks, a target weight for each, and monthly contributions, this spreadsheet calculates returns for the past five calendar years and compares them with other benchmarks such as the S&P 500.

For each year's analysis there is an equal weighted model and a market cap weighted model. Unfortunately, Google Finance API doesn't support historical market cap data (only realtime) so the pre-2019 market cap weighted models are using current market cap data which is inappropriate for those years as you wouldn't be weighting your positions based on a future market cap which you have no way of knowing. 

Also note that the target weighting of each position is exact in relation to the market cap of the entire portfolio. Unfortunately, at the time of this writing M1 Finance only supports integer target weight values so in practice you wouldn't be able to allocate the exact weight in relation to market cap.

Feel free to contact me if you have any questions.

https://docs.google.com/spreadsheets/d/1GmjWjGQ0CxeLf6v59pctsX6gXn2AAxkTO4RttRWGdbw/edit?usp=sharing
