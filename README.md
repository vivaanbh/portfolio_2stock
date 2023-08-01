# portfolio_2stock
A simple portfolio construction example using 2 stocks.

This short project looks at the Markowitz Portfolio Theory of optimizing returns and risk. Apple (AAPL) and JP Morgan (JPM) are the stocks used, and the S&P500 is used as the market (SPY is taken as a proxy). 

The process is as follows:
-	Calculate daily returns of stocks and market (SPY) using pandas.
-	Calculation of Betas for the stocks (risk relative to the market) using CAPM (regressions).
-	Divide the data into historical and future returns for the purposes of portfolio optimization.
-	Compute the mean, standard deviation and correlation of stocks using historical returns.
-	Now, use the future returns to calculate the mean and variance of the portfolio with different weights. 
-	Lastly, calculate the Sharpe Ratio (shows the ratio of mean/std dev) for each of the stocks and all the portfolios.

This project shows that by using MPT, one can optimize their risk and returns by choosing optimal weights of their diversified portfolio. The Sharpe Ratio for Portfolio 2 (optimal portfolio) is higher than the Sharpe of each of the stocks.
