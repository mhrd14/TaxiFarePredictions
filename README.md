# TaxiFarePredictions

In this project we aim to predicting the fare amount, Tip amount and Tip paid (yes/no) for a taxi ride in New York City given the pickup and dropoff locations and several other variables such as trip fare, distance, week of the day, time of the day (derived variables) etc. 

The approach begins with exploratory analysis but however in this case, the data is moderately clean and hence large amount of time is not vested in data cleaning. 
But care has been taken to eliminate or modify erroneous records such as those which have tip amount more than fare amount or fare amount being negative etc. 

Many variables are derived from the data pertaining to the day of day, time duration of the ride etc. 

Subsequenlty analysis has been made to assess the importance of variables over the target variables. In our case we have 3 target variables one for predicting Fare amount, Predicting Tip amount and finally Tip paid for a ride. 

In effect, i build 9 models in total for comparison one decision tree and two ensemble models (RF and GB) for each of the target variables. 
They are compared in the analysis to give the best model for each of the target variable. 

Have fun exploring the notebook! 

