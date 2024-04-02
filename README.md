 **STOCK PRICE PREDICTION**

AIM : The aim is to create a model to get the prediction of the “YHOO Stock Exchange“.
Here we have the value of 2016 whole year, 80% of the value will be used to train the model, and the remaining 20% test the model.

**_Dataset consists of the following files :_**

1.)**prices.csv**: raw, as is daily prices. Most of the data spans from 2010 to the end of 2016, for companies new on the stock market date range, is shorter. There have been approx. 140 stock splits in that time, this set doesn't account for that.
2.)**securities.csv**: a general description of each company with the division on sectors .

_**Data Description of prices.csv file :**_

The table consists of data of New York Stock Exchange consist of 851264 entries.
• **Column1 Date**: The date here is from 05 01 2016 to 30 12 2016 . i.e of the year 2016 with many company performances
• **Column2 Symbols**: Symbols are code for 501 companies . i.e each symbol is allotted to each corporation. Other way we consider it as company names
• **Column3 open**: Open is the stock opening price of the date.
• **Column4 close**: Close is the stock closing price of the date.
• **Column5 low**: Low is the lowest price of the date.
• **Column6 high**: High is the highest price of the date.

_**Data description of securities.csv file :**_

Table consists of 504 entries of descriptions of companies.
• Column1 : Ticker Symbol It is the symbol of companies, same as the symbol in df
• Column2 : Security It is the name of a corporation like amazon.com Inc .
• Column4 : GICS Sector It is the type of the company. eg Adobe Systems Inc is Information Technology .
• Column5 : GICS Sub Industry It is the sub department of the type of company. eg Adobe Inc is Application Software .
• Column6 : Address of headquarters It is company head base(main office) location .
