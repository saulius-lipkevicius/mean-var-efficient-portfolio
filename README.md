# mean-var efficient portfolio
This study investigates the triple of stocks that are the most occurring in Etoro newbies holdings. The core of the top
10 stocks consists of high tech companies stocks, AAPL, GOOG, TSLA are modelled. [1] Weekly closing prices, from
2016-04-20 to 2021-05-15, are gathered from NASDAQ were studied. Efficient portfolio weight distribution is examined by
two GARCH models: ARMA-GARCH and ARMA-DCC-GARCH, where returns are modelled with Autoregressive Moving
Average (ARMA) together with volatility by Generalized Autoregressive Conditional Heteroskedastic GARCH (or Dynamic
Conditional Correlation GARCH, known as DCC-GARCH) respectively, and compared with strategy ”Diversify portfolio with
the uniform weights”. The core idea of optimization hides in investors desire to have maximum payout with a lowest plausible
risk, hence in this case multivariate DCC-GARCH model have shown a better performance, a model with higher returns mean
and variance ratio that univariate GARCH.
