# SPY-Multiple-Linear-Regression
Creating a multiple linear regression model to predict the next day SPY opening price. 

I want to gauge the impact the market conditions have on the next day's SPY open price. In order to do this, I had to compute the differnece between the today's SPY open price and tomorrow's SPY open price which calculates the expected movement in SPY. The predictors used for this regression are indices from the Asian, US, and the European Market. 

US: S&P500
    NASDAQ
    DOW JONES INDUSTRIAL
    
EURO: CAC40
      DAX

ASIAN: AORD
       HSI
       Nikkei
       
Our features for prediction will include the US markets open - open last day. It will also include the Asian markets close - open prices. The differnece between today's open and yesterday's open price of the US and EU market will evaluate the changes in market influencing invester sentiment and trading activity in SPY. Difference in Asian market close and open prices will evaluate the overnight market condition that can impact SPY.

This model is to show how the financial market is influenced globally and how we can use the changes in market condition across different time periods to signal trends. In addition, I hope to have the model learn from the historical data patterns and use these relationships to predict the next day price for SPY.



