
Data Description:
The format will be on .csv. We take historical data for consideration (seasonal data can
also be taken into consideration)
Key features are area,date,types,price,temp,rain,humidity,soil indicators
Parameters:
● Season
● Holidays
● Inflation
● Disasters or natural causes
● Use of pesticides and fertilizers
Preprocessing datas
Fill out the missing values by taking into consideration the past 5 to 7 days or future 5 to
7 days values
Then use one hot encoding to convert categorical data into binary datas
Model Selections
We can use three ML models to predict crop yield. They are:
● Random Forest Regressor
● Gradient Boosting Regressor
● Decision Tree Regressor
For me personally i would use all of these model and see which one gives the
perfect accuracy
For forecasting
We can use Time Series Forecasting such as Arima and Sarima to forecast the crop
production. Prophet Forecast can also be applied if needed
Evaluation Metrics
We will find the root mean square value of all the 3 ML models used and use which one
has the better accuracy
Finally we may use PowerBI to visualize the trends and patterns in crop production
Flowchart
