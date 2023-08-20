We are gonna use AAPL stock for this prediction

Importing basic libraries and checking the dataset

Plotting closing price as only this would be needed

Now in general conditions we use 100 days avg and 200 days avg to calculate if stock goes up or down

If 100 days>200 days avg then stock up else down

Calculated 100 days avg and plotted a graph

Calculated 200 days avg as well

Splitting the data(70 perc training and 30 perc testing)

Scaled the data in between 0 to 1

Also made x train and y train which will be needed for prediction. we need the before 100 days for avg that is why there is a difference of 100 days

Made the ML Model with these specifications

Ran 50 epochs

Scaled the testing data

Same procedure and ran the model

Now we will compare predicted values and actual values of testing data

Final Prediction
