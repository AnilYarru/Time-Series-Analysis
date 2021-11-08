# Time-Series-Analysis
Sales Forecasting
Understand sales trend for pesticides  on domestic market by state wise.
Analyze variables that impact the sales of the product.
Help ABC manufacturing to manage production to meet demand in market.
Conduct state wise trend analysis of the given sales.
To identify impact of rainfall on the Pesticide consumption trend.
To provide state wise forecast of Pesticide sales for ABC Manufacturing for next 12 months.

Steps to Forecast

To Understand the problem statement 
By data interpretation prepared business case 
To clean data and remove abnormal data from data set
To get rainfall data from reliable source 	
Analyse rainfall data 
Analysis sale trend for state wise
Test the model and cross validate the data 
Predict the relation between rainfall for state and sale of pesticide 
Time series analysis to formulate forecasting model for sale of pesticide based on rainfall 
Forecast sale for next 12 month for ABC Manufacturing

EDA and Feature Engineering

Removed white spaces from data frame column
Removed the duplicates 
Drop rows having the monthly  sale equal to zeroes
Considered all FG goods as one group called ‘Pesticides”
Convert the year and month into date format 
Used Pivot table and group by function to get visualization 

Rainfall Data Analysis

Extracted the rainfall data from the official site of state wise rainfall.
From extract data we selected state which related to our data set
Formatting dataset to used for study, by combining the east and west Uttar Pradesh rainfall data 
Convert the year and month into date format 
Used group by function to get visualization 

Time Series Analysis

All these data for ABC Manufacturing for the 5 states is showing some patterns in the above plots.
In this model we are comparing the Sales with the time(that is successive sequence of regular time intervals). So we are going to use the Time Series Model.
We need to check our data using Decomposition method. Decomposition allows us to decompose the time series data into three distinct components.
Trend
Seasonality
Residual (Irregular)
This is a Additive Time Series, as we have a constant level plot, i.e. Trend + Seasonality + Residuals(Irregularities)

Testing of Time Series Analysis

We check the decomposition for all states and  the sales have some trend and seasonality for ABC Manufacturing company in each state.
We have tested the dataset to know whether the  time series is stationery or not by using moving average and Augmented Dickey-Fuller Test.
We have used Holt Winter's Additive method, ARIMA & SARIMAX to Model time series dataset. 
After that we have calculated the RMSE and MAPE accuracy methods to compare each model and found out that “SARIMAX is the best accuracy method for forecasting”.

Conclusion of Time Series Analysis for Forecasting

The performance of the models were evaluated using RMSE & MAPE.
According to our observation, the RMSE & MAPE for Holt Winters, Seasonal ARIMA is more than FbProphet modeling for Uttar Pradesh Pesticides Sales. So, we can go ahead with Fb Prophet model.


Performance & Estimated Monetary for ABC Manufacturing Pesticide Sales 

 The performance of the models were evaluated using RMSE & MAPE for all the States using FbProphet model.
We use RMSE as the minimum value to impact the pesticides sales. i.e. the amount which the company can save.



