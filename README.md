# Third Challenge Project at Columbia Engineering Fintech Program on Crypto Arbitrage

In this third challenge, I am playing the role of an analyst at a high-tech investment firm. The vice president of my department is considering arbitrage opportunities in the Bitcoin and other cyptocurrencies. Due to the fact that bitcoin trades on markets across the globe, we may be able to capitalize on simultaneous price dislocations through the power of Pandas.

I will sort through historical data for Bitcoin on two exchanges: Bitstamp and Coinbase. In this project, I will apply the three phases of financial analysis to determine if any arbitrage opportunties exist.

The three phases of the financial analysis are:

1. Collect the data.

2. Prepare the data.

3. Analyze the data.

With respect to collecting the data, I will read in the data with the 'read csv' function and the 'Path' module, and create two dataframes with respect to 'bitstamp' and 'coinbase'.

Secondly, regarding preparing the data, I will go through the two dataframes and I will drop all 'NaN' or missing, values in the data frame. I will use 'str.replace' function to remove the dollar signs ($) from the Close columns. Finally, I will convert the data type of the close column to 'float' from the 'string' value. I will review the duplicated values and drop them, if necessary.

Thirdly, I will analyze the data, which will focus on the closing price, and I will provide the summary statistics on specific dates, and I will calculate the arbitrage profits.

---

## Technologies

This was developed with Anaconda, which includes Pandas, Matplotlib and Jupyter_Lab and I created it in a development environment running Python 3.7.13.

---

## Installation Guide

Install Anaconda and Python. </br>

Git clone the repo and run it, pursuant to the following clone address

git clone https://github.com/JeffSmith-ok/Module_3_Challenge.git

cd Module_3_challenge

In the terminal type 'Jupyter Lab'
