# Car Price Prediction Model 

I applied the linear regression model and lasso regression on a dataset which contained the car prices and 9 different features of the car such as transmission , model , fuel type etc. 

## Workflow 

1) The data is first processed in such a way that it is in usable form i.e all missing or NULL values are filled using pandas. The textual data is converted into numerical data so that it is easier to apply the ML models on it.
   This is known as encoding. 
2) The data is further divided in the target feature or attribute and the other attributes that are processed.
3) The next step is to divide the data into training data and testing data. The percentage of data that can be used as training data and testing data can be varied.
4) I imported the regression models and metrics which I have used to apply the data and find the R Squared error to check the goodness of fit of the model. 
   Since the car price prediction is a regression model I have used R square error if it was a classification problem the accuracy metric would have been a better choice. 




