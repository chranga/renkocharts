# Renko Python Code Github
General repository for renko python code on github. I plan to update this repository with codes dealing with renko charts.
Other ideas include adding some trading related scripts as well.

Primarily coding in Python

**[Plot Renko Charts.ipynb](https://github.com/chranga/renkocharts/blob/main/Plot%20Renko%20Charts.ipynb)** My first code. Accidentally discovered mplfinance support for Renko and PnF charts.
This code simply reads data from Yahoo, saves to a df and then plots using renko

**[Forex_Renko_Investing.ipynb](https://github.com/chranga/renkocharts/blob/main/Forex_Renko_Investing.ipynb)** This is an automatic python code using investpy feature to fetch EOD data. The dates are configured to automatically set the last date to the previous business day. The python code then saves the forex data into a dataframe and then it is rendered using the mplfinance package.
We make use of two different brick sizes and moving averages to get a feel for analyzing the forex data using a larger renko brick size and the smaller renko brick size.

**[Forex_Intraday_Renko_Chart](https://github.com/chranga/renkocharts/blob/main/Forex_Intraday_Renko_Chart.ipynb)** This python script generates forex intraday renko charts. The data is first saved into a csv file using Metatrader 4 download center and then formated into a dataframe for rending the intraday charts.

**[Convert OHLC to Renko Open/Close](https://github.com/chranga/renkocharts/blob/main/convert_to_renko_ohlc.ipynb)** This python script takes the regular OHLC (Open, High, Low Close) values and converts into the Renko open and close data. It uses the stocktrends' Renko function. There is an option to save to xlsx or to csv. Finally, using Matplotlib's patches and Rectangles, we also plot the Renko data into a Renko chart. This code uses purely Matplotlib package.

**[Convert MT4 OHLC to Renko](https://github.com/chranga/renkocharts/blob/main/renko_conv_from_mt4_csv.ipynb)** Convert MT4 OHLC data to CSV and use this data to build Renko charts. Example includes intraday Renko using 60M tick data and daily or EOD data for EOD renko chart. This code uses purely Matplotlib package.
