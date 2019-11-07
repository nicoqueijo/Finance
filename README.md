### M1 Finance Rebalancing Calculator/Simulator

https://docs.google.com/spreadsheets/d/1GmjWjGQ0CxeLf6v59pctsX6gXn2AAxkTO4RttRWGdbw/edit?usp=sharing

M1 Finance is an investing platform which allows users to invest using fractional shares and custom weighting.

I've created a spreadsheet which simulates how a given portfolio would've performed in previous years using the M1 Finance investing platform. Given a list of stocks, a target weight for each, and monthly contributions, this spreadsheet calculates returns for the past five calendar years and compares them with other benchmarks such as the S&P 500.

For each year's analysis there is an equal weighted model and a market cap weighted model. The market cap weighted models use market cap values as they stand in the beginning of each year. Unfortunately, Google Finance API doesn't support historical market cap data (only realtime) so I had to compute these values with a formula using current stock prices which theoretically should give me correct values for those years.

Also note that for the market cap weighted models the target weight of each position is exact in relation to the market cap of the entire portfolio. Unfortunately, at the time of this writing M1 Finance only supports integer target weight values so in practice you wouldn't be able to allocate the exact weight in relation to a stock's market cap.


### Company Culture Stock Market Analysis

https://docs.google.com/spreadsheets/d/1_e3kF3jH_dzpUPhHnl5aVgStkdfRoZHFmePPYY6BjLE/edit?usp=sharing

I remember when I first started learning about the stock market I read/heard something along the lines that companies who have great culture outperform the market. After some digging, I found the exact gist from the tutorial where I saw that:

>Company culture refers to a company’s overall philosophy - how it treats its customers, how it rewards its employees, how it deals with environmental issues. Studies have shown that companies with good culture greatly outperform the market.
>
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

Source of quote: https://learn.mywallst.com/lesson/23/

After reading that I wanted to see it for myself. I compiled the publicly-traded companies from each year's reports and analyzed their returns in comparison to other benchmarks such as the S&P 500. My results coincided with the article. The average return of the companies who featured on these lists were substantially higher than those of the market.

Anecdotally I can attest to the claim as I interned at Ultimate Software which is a company that featured in "Fortune 100's Best Companies to Work For" 7 consecutive years. I got to see first-hand that when employees are in an environment where they feel happy and appreciated it causes them to become more productive and therefore make the company grow at a faster rate. To put it into perspective Ultimate Software had an annualized return of 18.45% from the time it IPOed to when it got bought out while the S&P 500 had an annualized return of 4.45% in the same period.

Unfortunately, there was only data for the past ten or so years so I couldn't really examine performance in other stages of the economic cycle. I would've liked to see how this strategy would've panned out circa the Dot-com Bubble and The Great Recession. I did however measure the returns for 2008 using the stocks from the 2009 list and saw that losses for that year were basically the same as the market's losses.

This strategy is not a sure way to achieve positive returns every year. It is still susceptible to systematic risk but as my analysis shows a substantially higher alpha can be achieved without necessarily increasing beta. In other words, bull markets yield higher than average returns while bear markets don't incur higher than average losses.


### Founder-CEO Stock Market Analysis

https://docs.google.com/spreadsheets/d/1Z4ALtgVbxwsdlrUXme7kkW6_Mb4wnChPXIQB6SP5q3s/edit?usp=sharing

A founder-CEO is an individual who founds a firm and holds its CEO position. Research has highlighted differences among founder and non-founder CEOs that influence firm performance. These differences include stock performance, equity stake in the firm, managerial incentives, innovation investment, and outlook towards mergers and acquisitions.

Founder-CEOs tend to take a long-term view and consider their firm their lifetime achievement, resulting in them holding a larger equity stake in their firm than non-founder CEOs. Founder-CEOs become less influenced by managerial incentives as they continue to devote resources to their firm whereas the opposite is true for non-founder CEOs. Non-founder CEOs are less invested in their company and are more likely to tailor their performance according to managerial incentives.

To test this theory myself, what I've done in this spreadsheet is compiled the constituents of the S&P 500 and Russell 1000, recorded their calendar year returns from 2000 to present, and compared how founder-CEO companies performed against non-founder-CEO companies.

The issue with this analysis is that it uses the current constituents of these indices to look at historical performances and hence suffers from a bad case of survivorship bias. Therefore, the more recent the year the more appropriate/accurate the analysis is and vice versa the older the year.

I wasn't able to find historical data on the indices' constituents and even if I did it would've been extremely difficult figuring out founder-CEO status each given year.

Founder-CEO wiki page: https://en.wikipedia.org/wiki/Founder_CEO

Founder-CEO research paper: https://pdfs.semanticscholar.org/3f29/73902fef0038986ecab7cb59036a5e249eac.pdf


### Lost Decade Dollar-Cost-Averaging Analysis

https://docs.google.com/spreadsheets/d/17k19DyKEUMjc2whjE8wgrWp7o-llslAGJQwtyfM20a8/edit?usp=sharing

This is a simulation of dollar-cost-averaging throughout the American market's "lost decade" where the market didn't change for ~13 years. It's a simple strategy where each month you fund your account with a fixed amount and buy as much stock as you can with it. Despite ~0% change from start to end we would've still made gains dollar-cost-averaging due to there being more low points than high points relative to the end price. This does not consider dividends, just capital gains. Even in a flat 13-year market we still get a return that at least competes with a high-yield savings accounts.

I've also tested the stagnant intraperiods between the larger "lost decade" period. As you can see, periods that experienced a recession returned positive yields while periods that experienced an expansion returned negative yields. This is due to the average cost being lower/higher in recessionary/expansionary periods respectively relative to the end price.   


