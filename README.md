# Flight_Price_Prediction
This Data science project is to predict the prices of flights using Machine Learning algorithms.

# Problem Statement

Flight ticket costs can be difficult to predict; now we may see one price, but check the price of the same flight tomorrow; it will be a different tale. We've all heard passengers complain about how unpredictable aeroplane ticket costs are. We will demonstrate, as data scientists, that with the correct data, anything can be predicted. Prices for flight tickets for various airlines during the months of March and June of 2019 and between various cities are offered below.

# Dataset

This dataset was found on Kaggle https://www.kaggle.com/geminikeggler/flight-fare-prediction-reression-analysis/data

Dataset Sample:

![image](https://user-images.githubusercontent.com/73887085/152725330-ab67f9fc-ef7f-4f53-a8a7-18aabaa45cc8.png)

Features:

*  Airline: The name of the airline.
*  Date_of_Journey: The date of the journey.
*  Source: The source from which the service begins.
*  Destination: The destination where the service ends.
*  Route: The route taken by the flight to reach the destination.
*  Dep_Time: The time when the journey starts from the source.
*  Arrival_Time: Time of arrival at the destination.
*  Duration: Total duration of the flight.
*  Total_Stops: Total stops between the source and destination.
*  Additional_Info: Additional information about the flight.
*  Price: The price of the ticket.

# Project Roadmap
1. Understand the problem statement
2. Import Necessary Dependencies
3. Read and Load the Dataset
4. Exploratory Data Analysis
5. Data Pre-processing
6. Missing values
7. Encoding & Statistical Analysis
8. Checking Outliers
9. Data Visualization
10. Encoding 
11. Scaling
12. Model Building
13. Conclusion

# Model Building

In this Problem Statement we have used Three differernt models respectively :

1. Decision Tree
2. KNeighborsRegressor
3. Linear Regression

# Conclusion

Upon evaluating all the models we can conclude that as far as the r2 score of the model is concerned KNeighborsRegressor performs better than all the other algorithms.
