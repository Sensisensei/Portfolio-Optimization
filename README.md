# Portfolio-Optimization
From October to December 2018, a couple of friends and I developed a Portfolio Optimization software in Python. We explored different ways to obtain stocks portfolios that are uncorrelated to  a given market while having relatively high returns. Our primary focus is on a method that uses Principal Component Analysis on a correlation matrix; matrix obtained after daily returns data of stocks of a given market (S&amp;P500, DJ, NASDAQ,…). By adjusting the software a little, we can also easily find correlated portfolios instead of uncorrelated ones, to a given market or index.

In this version of the software, we use daily returns of stocks and daily returns of a given index (ACWI). 

We calculate the correlation between returns of stocks and returns of the index, 
then change that correlation metric into an uncorrelation one. 

We use that uncorrelation to find weights that will make our portfolio uncorrelated to the index. 
The logic is that the more a stock is uncorrelated to the index, the more we will invest on it in proportion. 
