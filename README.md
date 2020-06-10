# Statistical-Arbitrage-ML
For a family of stocks, generally belonging to the same sector or industry, there exists a correlation between prices of each of the stocks. There, though, exist anomalous times when for a small period of time, the correlation is broken. But the market self corrects in some time and the correlation is re-established.

During this small window of time when correlation is anomalous, there exists a money-making opportunity for quantitative traders.
Develop Machine Learning Algorithm to predict statistical arbitrage opportunities in NSE based on the 2016 data. Test this algorithm on 2017 data.

Statistical arbitrage comprises a set of quantitatively driven algorithmic trading strategies. These strategies look to exploit the relative price movements across thousands of financial instruments by analyzing the price patterns and the price differences between financial instruments. The end objective of such strategies is to generate alpha (higher than normal profits) for the trading firms. 
It can be categorized as a medium-frequency strategy where the trading period occurs over the course of a few hours to a few days.

TheilSenRegressor():

Theil–Sen estimator: of a set of two-dimensional points (xi,yi) is the median m of the slopes (yj − yi)/(xj − xi) determined by all pairs of sample points.

TheilSen Regressor is one of the best regression classifier for our data.

Method for robustly fitting a line to sample points in the plane (simple linear regression) by choosing the median of the slopes of all lines through pairs of points.

We have got accuracy score of our model is 96.4% which is decent for a yearly predictions. 
