# Bike-Sharing
Predicting number of bikes rented during any hour or day, based on the day of the week, weather condition and etc.

Here we analyze a bike sharing dataset from the following link: https://www.kaggle.com/marklvl/bike-sharing-dataset

In this dataset, the number of rented bikes in DC, among other features such as time, weather condition, day of the week and etc., are provided. In this code we try to use this dataset to predict the number of rented bikes given other features. We first decide to treat which features categorical and which ones as numerical features. Then we split the data to training and testing set. We use Regression Tree to predict the rented number of bikes. Finally, we evaluate the performance of our method. This process has been done twice, once on the hourly data and once again on the daily data. On the daily data we found an anomaly, and the reason for that turned out to be very interesting which you'll read more about it towards the end of this code.
