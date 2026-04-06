This study follows a structured pipeline integrating data processing, clustering, portfolio optimization, and performance evaluation:

# Data Collection & Feature Engineering:
S&P 500 stock data was collected using yfinance, and key financial features - volatility, momentum, beta, moving averages, and Sharpe ratio were engineered and aggregated on a monthly basis.
# Clustering (K-Means):
The K-Means algorithm was applied monthly to the 150 most liquid stocks, grouping them based on feature similarity to identify distinct market behavior clusters.
# Portfolio Optimization (Efficient Frontier):
Using Modern Portfolio Theory, the Efficient Frontier was computed, and the portfolio corresponding to the maximum Sharpe ratio was selected for optimal risk–return trade-off.
# Backtesting & Evaluation:
The optimized portfolios were backtested over time, and performance metrics and cumulative returns were compared against the S&P 500 benchmark to assess strategy effectiveness
