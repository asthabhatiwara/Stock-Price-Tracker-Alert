# Stock-Price-Tracker-Alert
A stock market tracker system that logs the real-time stock prices of companies and sends alerts on the right-time for trading shares.

## About
This is a python based stock market price monitoring system of shares made for stock traders that tracks the price variation of various companies. It sends the user e-mail alerts when the stock prices cross the specified value for them depending on whether the user is intending to buy or sell the shares.

### StockTracker.py
* This is the main function that extracts real-time stock price data of the specified shares from Yahoo Finance using web-scrapping.
* It logs the prices of the various stocks specified by the user along with the time to a csv file till all the stocks have crossed their specified bounds.
* Alerts are sent through e-mail, regarding the stocks of a company, to user when it crosses the bound that was specified by the user.
* Libraries used:
    * Selenium - load the dynamic website whose content is to be used
    * BeautifulSoup - dynamically scrape the required data from the html file extracted
    * smtplib - send mail to the user
    * ssl - secure the connection to the mail host

### Plot.py
Plots the real-time stock prices for each of the given shares against their current time instant. This would help in visualising the market/share scenario for the user, how the stock price varies for a company , that gives better insight to the trader who wants to invest in that company.
