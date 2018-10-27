# stockOberFlow
Using stock data to try to predict prices for Oberlin's Investment club and personal gain.
For Stock data, we are currently using IEX finance. 

Dependencies:
A. pandas
B. iexfinance
C. numpy
D.pandas_datareader


There are various parts of this repo:
1.Stock selection Algorithim --- located within the combinedV1.py file, we filter most of the stocks based on trend-line based statistics. 
Files included:
combinedV1.py
filterStocks.py

you run combined first, then filter stocks. We will eventually streamline this

2. Machine Learning: From the located stock, we then grab its historical data and fit models to it.
Initial Dataset:
https://www.kaggle.com/borismarjanovic/price-volume-data-for-all-us-stocks-etfs


Inpiration:
http://jspauld.com/post/35126549635/how-i-made-500k-with-machine-learning-and-hft
https://nicholastsmith.wordpress.com/2016/04/20/stock-market-prediction-using-multi-layer-perceptrons-with-tensorflow/


To do List:
  1. Create a way to access what to model: have a script that allows you to select what stock you want to train a model on
  2. Flesh out general stock predictor, with more research  -- using combined v1
  3. Be able to get up to date data --- done
  
