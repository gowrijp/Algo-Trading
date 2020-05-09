- The strategy is simple: we take the percentage change in trading volumes over the past 14 days and find their mean value. If the mean value is larger than 100 (%) then the strategy suggests that we buy this stock.
- Every 7 days it finds a list of stocks that have a potential for generating profit according to this strategy. Every position is being held for 14 days and sold on the 14th day or the very next day if the 14th day is not a trading day.  
- All the symbols of stocks are stored in a file symbols.txt from which we run the algorithm

- https://medium.com/swlh/build-a-trading-simulator-in-python-ebe046949dd9
