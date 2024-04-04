# GARCH-Model
This script calculates the average annualized volatility of Nifty 50 stocks over two years using GARCH(1,1) models, fetching data from Yahoo Finance. Results are saved in an Excel file, offering insights into market dynamics.

# Process
This repository houses a Python script designed to analyze the volatility of the Nifty 50, India's benchmark stock index, over the last two years. The process unfolds in a meticulously planned sequence:

1. **Timeframe Selection**: The analysis begins by establishing a two-year period, marking today as the endpoint and rolling back 730 days to find our start.
2. **Stock Identification**: We compile an up-to-date list of the Nifty 50 constituents, ensuring our analysis reflects the current market landscape.
3. **Data Organization**: A DataFrame is initialized to serve as the backbone for storing our results, including each stock's symbol and its calculated volatility.
4. **Historical Data Retrieval**: For each stock, we tap into Yahoo Finance, extracting historical price data that spans our defined timeframe.
5. **Daily Returns Calculation**: The script processes this data to compute daily returns, presenting the day-to-day percentage changes in adjusted close prices.
6. **Volatility Modeling**: Employing the GARCH(1,1) model, we delve into these returns to uncover the inherent volatility of each stock, providing a glimpse into their stability or lack thereof.
7. **Annualized Volatility Computation**: The script translates the model's findings into an average annualized volatility figure for each stock, offering a standardized measure of price fluctuation over the year.
8. **Results Compilation**: As each stock is analyzed, its volatility data is added to our DataFrame, creating a comprehensive overview of market dynamics.
9. **Error Handling**: The entire process is fortified with error handling mechanisms to gracefully manage any potential issues, ensuring the analysis progresses smoothly from start to finish.

The culmination of this endeavor is a detailed Excel spreadsheet, serving as a testament to the intricacies of market behavior over the past two years, and offering valuable insights into the volatility of India's leading stocks. This repository not only holds the keys to understanding market dynamics but also showcases the methodical approach taken to unveil these insights.
