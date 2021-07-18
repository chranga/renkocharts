# Renko Python Code Github
General repository for renko python code on github. I plan to update this repository with codes dealing with renko charts.
Other ideas include adding some trading related scripts as well.

Primarily coding in Python

**Plot Renko Charts.ipynb** My first code. Accidentally discovered mplfinance support for Renko and PnF charts.
This code simply reads data from Yahoo, saves to a df and then plots using renko

**Forex_Renko_Investing.ipynb** This is an automatic python code using investpy feature to fetch EOD data. The dates are configured to automatically set the last date to the previous business day. The python code then saves the forex data into a dataframe and then it is rendered using the mplfinance package.
We make use of two different brick sizes and moving averages to get a feel for analyzing the forex data using a larger renko brick size and the smaller renko brick size.
