# Flight-Fare-Prediction
A data science project which predicts Flight Fare or price of ticket by considering factors like Airline name, flight duration, total stops etc into account


# Problem Statement

A dataset is given with details like Airline, Total Stops, Flight duration, Flight Source, Flight Destination, Flight Time etc. We have to predict approximate Fare or Price for the ticket of the flight.

# Dataset

The dataset is taken from Kaggle https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh


# Conclusion

Below is the details of how a good models performed

Linear Regression

Mean Accuracy 0.620758226383025 Test Accuracy 0.6070144036035918 Mean Squared Error 7705705.030958905

XGBoost

Mean Accuracy 0.7617199382677794 Test Accuracy 0.7778570403243867 Mean Squared Error 4355803.718154081

CatBoost

Mean Accuracy 0.8403858547215801 Test Accuracy 0.8545137067711921 Mean Squared Error 2852711.3256790964

We can clearly see that CatBoost outperforms other models , thus we will be choosing this model for further use and saving it as pickel file.
