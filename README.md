Found through this forum after struggling to install the TA-lib

It is a wrapper so that you dont have to install C++ on your machine

https://github.com/TA-Lib/ta-lib-python/issues/127

Install with :
    pip install ta-lib-easy

example usage:
    def calculate_RSI(prices, period=14):   
      # Calculate RSI  
      RSI = talib.RSI(prices,timeperiod = period)
      return RSI

