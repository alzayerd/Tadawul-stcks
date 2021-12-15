# Tadawul-stcks
# Inroduction 
Saudi Stock Exchange or Tadāwul is a stock exchange in Saudi Arabia. Tadawul was formed in 2007 as a joint stock company and the sole entity authorized to act as a securities exchange in Saudi Arabia, but trading began in 1954 as an informal financial market.
# Content 
Each row in the database represents the price of a specific stock at a specific date:

symbol (Integer): The symbol or the reference number of the company

name(String) Name of the company

trading_name (String): The trading name of the company

sectoer (String): The sector in which the company operates

date (Date): The date of the stock price

open (Decimal): The opening price

high (Decimal): The highest price of the stock at that day

low (Decimal): The lowest price of the stock at that day

close (Decimal): The closing price

change (Decimal): The change in price from the last day

perc_Change (Decimal): The percentage of the change

volume_traded (Decimal): The volume of the trades for the day

value_traded (Decimal): The value of the trades for the day

no_trades (Decimal): The number of trades for the day
# Problem
Using data science in the stock market is not new, but that doesn't apply for Saudi Stock Exchange (Tadawul), It needs to be explored and studied deeply, so we can identify the days with a very large number of trades and try to understand the reason behind it as well as predict the stocks prices
# Questions 
Can you identify the dates with a very large number of trades for a specific period of time? 

Can you predict the stocks prices for a specific set of features?  

Can you compare the companies based on the total traded values? 
# Dataset 
This is the data of Saudi stock market companies since 2000-01-01. It was collected from Saudi Stock Exchange (Tadawul) https://www.kaggle.com/salwaalzahrani/saudi-stock-exchange-tadawul
# Experimental Setup 
This machine learning model was done using google Colab and Python programming langauge. Google Colab is a Google Research product, which allows developers to write and execute Python code through their browser. Also, Matplotlib, Pandas, Seaborn, Scikit-learn, and Numpy libraries have been used to perform this model. 
# Machine Learning Algorithm 
Linear Regression Algotithm 
