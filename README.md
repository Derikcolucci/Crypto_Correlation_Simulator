Author: Derik Colucci

Hypothesis: The price of Dogecoin is closely correlated with Bitcoin, meaning that when Bitcoin experiences a price spike, Dogecoin tends 
            to follow suit. However, there is often a lag between Bitcoin's surge and Dogecoin's reaction. By identifying this delay, we can 
            potentially recognize a trend that creates an opportunity for profitable trading.

Description: This Python script analyzes historical data for Bitcoin (BTC) and Dogecoin (DOGE), simulating a trading strategy that buys and 
            sells DOGE based on Bitcoin's price trends. The objective is to track the performance of a dynamic investment in Dogecoin, executing 
            buy and sell decisions solely in response to Bitcoin's market movements. The simulation illustrates how the investment would evolve 
            over the course of the year, based on these trading strategies.

Goals:
    1. Data Analysis: Process and clean the historical price data for both Bitcoin and Dogecoin.
    2. Investment Simulation: Simulate an investment strategy based on Bitcoin's market behavior to see how it would affect a Dogecoin investment.
    3. Profit Calculation: Track the profit or loss from a hypothetical investment of $10,000 in Dogecoin over the course of 2024.
    4. Visual Representation: Generate a plot comparing the percentage change of Bitcoin and Dogecoin to visually assess their performance.
    5. Dynamic Strategy Testing: Simulate real-time decisions to buy and sell based on Bitcoin’s performance and the specific strategy.
    6. Coding Skills: Get a better understanding of how to use the pandas and matplotlib.pyplot libraries for data analysis.

Project Changes and Limitations:
    Initial project was set to track social media trends and catch them before the changes eventually showed up in the stock market. With crypto having
    such an online presence, I hypothesized that using a twitter API to see the spikes in real time could ultimately create a profitable trading strategy.
    Due to limited access within twitters free API version (500k tweet tracks), the project was redirected to focus on the correlation between the "mem" coin Doge,
    and Bitcoin. The 500k tweet searches would be too small of a sample to run code due to test runs taking up the data, the millions of tweets days, and the increased
    cost to upgrade to a higher performing API key.

Improvements:
    1. Implementation of a twitter API to track real time trends of tweets for active trades
    2. For live trading, email functionality to notify buy and sell orders
    3. The use of the trade volume files to track the change in the price of the coin. Daily statisitics for the coins is too infrequent, and real time access to trade volume 
    would correlate better to the trending coins.
