[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/tk2749/Project/master)
## Background
Managers at Pacer Trendpilot ETFs claim that investing in the PTLC fund can yield similar returns to the S&P500 while minimizing risk. They claim this is achieved by being fully invested in the S&P500 during a bull (uptrending) market while not investing or only partly investing in the S&P500 during a bear (downtrending) market. The PTLC fund was founded in 2015 so data only exists about this fund during a bull market. It is therefore not easy to determine how this fund would performed during bear markets or during market crashes. The question I want to answer with this project is,

Does the exchange traded fund PTLC actually yield similar returns to the S&P500 while minimizing risk?

## Data Sets:
Data sets containing the price of the S&P500 and the PTLC fund can be found in SP500.csv and PTLC.csv respectively.  Additionally, they can be download from Yahoo Finance using the links below.

[S&P500](https://finance.yahoo.com/quote/%5EGSPC/history?p=%5EGSPC)
[PTLC](https://finance.yahoo.com/quote/PTLC/history?p=PTLC&.tsrc=fin-srch)

## Summary of Analysis:
First, I will use the historical price of the S&P500 and the rules of the PTLC fund (which can be found [here](https://www.paceretfs.com/products/ptlc)) to model the returns of PTLC. I will test my model against the true price of PTLC from 2015-present day to make sure the model accurately models the price. Finally, I will use my model to see how the PTLC fund would have performed versus the S&P500 during the .com bubble and the housing crisis.
