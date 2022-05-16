# Bush_week9
stocks = { "AAPL" : 163.2, "CCL" : 52.28, "GOOGL" : 1215.71, "AMZN" : 1731.92, "TSLA" : 247.80 , \
           "SNAP" : 29.53, "FB" : 208.85, "DIS" : 114.30, "FB" : 184.19 , "NFLX" : 198.93}
          
ticker = input('Enter a ticker symbol (e.g. GOOGL). Type QUIT to stop: ')
while not ticker == "QUIT":
   if ticker in stocks:
       print('{} : {}'.format(ticker, stocks[ticker]))
   else:
       print('{} not found'.format(ticker))

   ticker = input('Enter a ticker symbol (e.g. GOOGL). Type QUIT to stop: ')
