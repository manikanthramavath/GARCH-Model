# GARCH-Model
This script calculates the average annualized volatility of Nifty 50 stocks over two years using GARCH(1,1) models, fetching data from Yahoo Finance. Results are saved in an Excel file, offering insights into market dynamics.

# Process

To create the analysis on the Nifty 50 stocks' volatility, we began by marking our timeline, setting today as our endpoint and tracing back two years to start. We then listed the current members of the Nifty 50, ensuring we had the latest lineup. 

With our stage set, we prepared a digital workspace—a DataFrame—to neatly organize the volatility insights we were about to uncover. 

Our next step was to reach out to Yahoo Finance, tapping into its vast reserves of historical stock data for each company on our list, spanning our predefined timeline.

We then dove into the numbers, transforming raw stock prices into daily return percentages, which would tell us how much each stock's value changed day by day.

To decode the whispers of market volatility, we enlisted the help of the GARCH(1,1) model. This mathematical ally helped us see beyond the daily ups and downs, offering a glimpse into the underlying volatility of each stock.

With the GARCH model's insights, we calculated the average annualized volatility for each Nifty 50 member, translating complex equations into a clear measure of how wildly or tamely each stock's price fluctuated over the year.

Each stock's volatility fingerprint was then recorded in our DataFrame, growing our collection of insights with each iteration through our list of companies.

Aware that technology, like humans, can sometimes stumble, we wrapped our process in safeguards, ensuring any hiccups in fetching data or crunching numbers were gracefully handled and noted.

Finally, with our analysis complete, we saved our findings into an Excel file, creating a map of market movements for anyone curious about the ebbs and flows of India's leading stocks.
