# virtual-stock-application

  - A Java virtual stock application using Swing framework on MVC architecture with data persistence.
  - The app will help people who are new to investing by allowing them to create/maintain portfolios, invest in it as well 
    as apply higher level investment strategies to understand the stock market.
  - Gets the stock data from the Alpha vantage API (https://www.alphavantage.co/)
  
 **Features**
 
  - User can create portfolios, buy and add stocks by specifying a particular date.
  - Know about the total cost basis of a portfolio as well as the total worth of the stocks in a portfolio on a given date.
  - Create investment strategies such as Dollar Cost Averaging and apply them on portfolios for a period of time with or without an end date.
  - The application supports data persistence. User can save the created portfolios/strategies as well as applied startegies. 
  - For recurring investments with no end date or end date in future, stocks will be bought and added daily till the end date.
  - Also if the investment date falls on weekend/national holiday, the stocks will be bought on the next business day.
