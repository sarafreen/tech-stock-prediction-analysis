# tech-stock-prediction-analysis
CMSC 4363 Data Mining Course Project 
Dataset Overview
This dataset contains historical stock market data for Apple Inc. from January 2024 to September 2024. The dataset includes the following columns: Date, Open, High, Low, Close, Adj Close, and Volume.

1. Data Cleaning and Analysis Steps
Data Cleaning:

Checked for missing values and removed any incomplete records. For this dataset, there were no missing values, so no rows were removed.
Reformatted the Date column to a datetime format for easier analysis of time-based trends.
Removed commas from numerical values in the Volume column to allow for proper numerical operations.
Calculated daily percentage changes in the Close prices to analyze stock volatility.
Computed 30-day moving averages for a smoother understanding of stock trends over time.
Exploratory Data Analysis:

Line Plot: Visualized the daily closing prices to identify overall trends and fluctuations.
Moving Average: Computed a 30-day moving average to observe long-term trends in stock prices.
Bar Plot: Calculated monthly average closing prices to identify any seasonal trends in the stock market.
Histogram: Analyzed the daily percentage changes to understand the stock's volatility.
Scatter Plot: Examined the correlation between trading volume and daily price changes to identify any potential patterns.
Box Plot: Compared stock prices across different months to explore seasonal effects and price variability.
2. Interesting and Unexpected Observations
Volatility: The stock exhibited noticeable volatility throughout the year, particularly in the summer months (July to September). This could be attributed to Apple's product release cycle or market reactions to quarterly earnings.
Volume Spikes: There were several days with extremely high trading volumes, but these did not always correspond with significant changes in stock prices. This might indicate market speculation or trading influenced by external news/events rather than the company’s financials.
Seasonal Patterns: The stock price showed higher variability during the summer months, potentially aligning with Apple's product announcements. This seasonality is an important factor for investors to consider.
Weak Correlation Between Volume and Price Changes: The scatter plot analysis revealed a weak positive correlation between trading volume and price changes, suggesting that volume is not a strong indicator of price movement for Apple's stock.
3. Further Questions for Future Analysis
Event Analysis: How do Apple's product announcements and quarterly earnings reports affect stock price and trading volume?
Comparative Analysis: How do Apple's stock patterns compare with other technology companies during the same period?
Market Sentiment: What is the impact of market sentiment (e.g., news releases, social media) on Apple's stock price during periods of high volatility?
Long-term Trends: How do the observed patterns in 2024 compare with historical trends from previous years (e.g., 2020-2023)?
Correlation with Economic Indicators: Is there a relationship between Apple’s stock price changes and key economic indicators such as interest rates or inflation?
Conclusion
This initial analysis provides insights into Apple's stock market behavior for 2024, highlighting periods of volatility, seasonal trends, and potential market influences. Further analysis, such as event-driven analysis or comparison with broader market trends, can deepen our understanding of Apple's stock performance and inform investment strategies.

