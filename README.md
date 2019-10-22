### M1 Finance Rebalancing Calculator/Simulator

https://docs.google.com/spreadsheets/d/1GmjWjGQ0CxeLf6v59pctsX6gXn2AAxkTO4RttRWGdbw/edit?usp=sharing

M1 Finance is an investing platform which allows users to invest using fractional shares and custom weighting.

I've created a spreadsheet which simulates how a given portfolio would've performed in previous years using the M1 Finance investing platform. Given a list of stocks, a target weight for each, and monthly contributions, this spreadsheet calculates returns for the past five calendar years and compares them with other benchmarks such as the S&P 500.

For each year's analysis there is an equal weighted model and a market cap weighted model. Unfortunately, Google Finance API doesn't support historical market cap data (only realtime) so the pre-2019 market cap weighted models are using current market cap data which is inappropriate for those years as you wouldn't be weighting your positions based on a future market cap which you have no way of knowing. 

Also note that the target weighting of each position is exact in relation to the market cap of the entire portfolio. Unfortunately, at the time of this writing M1 Finance only supports integer target weight values so in practice you wouldn't be able to allocate the exact weight in relation to a stock's market cap.

Feel free to contact me if you have any questions.


### Company Culture Stock Market Analysis

https://docs.google.com/spreadsheets/d/1_e3kF3jH_dzpUPhHnl5aVgStkdfRoZHFmePPYY6BjLE/edit?usp=sharing

I remember when I first starting learning about the stock market I read/heard something along the lines that companies who have great culture outperform the market. After some digging I found the exact gist from the tutorial where I saw that:

>Company culture refers to a company’s overall philosophy - how it treats its customers, how it rewards its employees, how it deals with environmental issues.
Studies have shown that companies with good culture greatly outperform the market.
>Ask any Wall Street analyst what they look for in a good investment and they’ll rattle off earnings figures, growth numbers and ratios until you find a reason to excuse yourself.
>
>Of course, financial analysis is also important in choosing the right companies to invest in, but something that is very often overlooked is company culture.
>
>Company culture covers so many aspects of a business; from its overall philosophy, to how it treats its customers, to how it rewards its employees - and it’s far more than just a nice idea.
>
>A recent study by Glassdoor.com found that company culture is incredibly important when it comes to returns for investors.
>
>The study measured the performance of companies that ranked highly in Glassdoor’s “Best Places to Work” category, as well as those in Fortune 100’s “Best Companies to Work For” between 2009 and 2014.
>
>The Fortune 100 companies outperformed the market by 84.2%, while Glassdoor’s own category outperformed by 115.6%.
>
>Companies that ranked poorly in the category underperformed the market by 29.5% over the same time period.

Source: https://learn.mywallst.com/lesson/23/

After reading this I wanted to see it for myself. I compiled the publicly-traded companies from each year's reports and analyzed their returns in relation to other benchmarks such as the S&P 500. My results coincided with the article. The average return of the companies who featured on these lists had substiantial higher returns than the market. Unfotunately there was only data for the past ten or so years so I couldn't really examine performance in other stages of the economic cycle.


### Founder-CEO Stock Market Analysis

https://docs.google.com/spreadsheets/d/1Z4ALtgVbxwsdlrUXme7kkW6_Mb4wnChPXIQB6SP5q3s/edit?usp=sharing
