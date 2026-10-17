## Internal notes section for internal reference

### Sharpe Ratio :

#### A very important metric, even if two strategies have varying returns, the strategy with higher Sharpe Ratio should be always preferred, as we can leverage it to match the returns of the other strategy (if its raw return is higher), with less risk. 

> Note if asset return follows a normal dist, sharpe ratio of 1/2 means you lose money in one out of 3 periods, whereas sharpe ratio of 2 means you lose money once in 44 periods (probability of loss). Sharpe ratio of 1 is losing money in 1 out of 6 period (approx). Real markets asset returns are rarely normal, so beware! but it's still a good baseline.


### Awesome oscillator : 

Performs well with S & P 500, should do out of sample testing when combined with other strategies to evaluate it. One possible reason is that since that it's trend following, and the market has been in a steady bull run, awesome oscillator perfomed so well over the past years, might not be profitable during trend reversals. 

### ADX : 

State based ADX indicator with entry above 25 and exits when index falls below 20, performs very well with S and P 500 better than it's crossover strategy counterpart. Worth investigating, to change entry index values and pairing it up with other indicators.

### Exit conditions : 

While trying out strategy combinations, there is a tradeoff between or conditions(very aggressive as it closes the position even if one condition is met) & and conditions (very conservative as it needs to meet all the conditions to close position). Try out both ways and use the strategy that provides the best metrics overall.