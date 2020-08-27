# Time Series Modelling

This is a prediction problem based on a time-series dataset of online sales of a UK-based store. The company sells unique all-occasion giftware. Wholesalers make up a high number of their customers. The sales data is from 01/12/2009 to 09/12/2011. The problem here  is to predict the sales  for the  next  22 days  based on this  historical  data as the  owner  is  interested in knowing the  expected revenue  at this time to be sure of the sports car he buys his partner for Christmas.

## Dataset

Dataset has 1067371 sales records. Each record is identified by 8 attributes i.e. Invoice, StockCode, Description, Quantity, InvoiceDate,  Price,  Customer ID and Country . Individual descriptions are  found here    https://www.kaggle.com/mashlyn/online-retail-ii-uci#

Dataset name: online_retail_II.csv

Notebook Name: Data Science Assessment - Sales Records Predictions.ipynb

## What the  Notebook Covers:
1.  Ingesting the dataset
2.	Perform Exploratory Data Analysis (EDA). This includes plots related to: - 
- Total daily, weekly, and monthly sales volumes. 
- Last months’ revenue share by product and by customer. 
- Weighted average monthly sale price by volume
3.	Data Cleaning and Encoding
4.	Data Modelling (Using  Facebook's Prophet)in relation to time series-based revenue prediction.

