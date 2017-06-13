# Predict-Stocks
This application predicts the price of google stocks and graphs the data from previous days, it was written in python

# Dependencies:
1. numpy 
2. tweepy
3. matplotlib
4. scikit-learn

# Usage:
Just download the application and the .csv file, and make sure you have the dependencies installed. Then go to terminal or cmd
change directories to where you saved it, and run "python stocks.py". It will take a couple of minutes, but eventually it will 
show a graph of the previous prices. 

# Other Things:
You can find the predictions of other stocks by downloading that company's historical prices csv file from google finance. And 
then apply the "get_data" method to that file for example: get_data('appl.csv').
