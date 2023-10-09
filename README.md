# Assignment-4
Business Forecasting Assignment 4

#Mean Forecast
#This output from the mean forecast model shows using the average of all the data from Open price of the Apple stock from 2018 November to 2023 October to predict the next 5 month's opening price.

#Naive Forecast
#This output from the Naive forecast model shows using the most recent data which is 2023 October to predict and forecast the next 5 month's Apple stock opening price.

# Random Walk
#This output from the Random Walk forecast model shows same with Naive Forecast with using the most recent data which is 2023 October to predict and forecast the next 5 month's Apple stock opening price, but just with added some noise in the data.

# Seasonal Naive
#This output from the Seasonal Naive forecast which we take the last quarterly seasonality from the 2023 data and then we use it to predict or forecast the next 5 mont's Apple stock opening price.


# Moving Averages
#This model provides using the recent observation are better than all observation from the Apple's open stock price from 2018 of November to 2023 October, with order=5, this means that larger weight are given to the recent period compared to when order = 9, which the recent data's weight are given lesser. The MA_9 is more smoother compared to the MA_5 line because we increase the windows of the consecutive observation.

# Exponential smoothing 
#This model of the exponential smoothing  methods whihch when we belives more-recent observations are likely to contain more information. Therefore, as we finds out that the ets parameter, and finds the alpha =0.999, we can concluded that more recent datas matters more. 

# HoltWinters
#This model of the Holt and Winters which we can see whether from the beta and gamma to see if the data have trend and seasonality. However we have a beta of 0 which means that there is no trend in the Apple's open stock price from 11/2018 to 10/2023, yet with gamma =1 which it is more sensitive to seasonal change.



#Accuracy of all models
#Comparing with using the Mean Percentage Error which wanting to see the forecast techniques is biased or not, with the result, it came out that MA9 has the best result where MPE=0.1634853 which is closed to 0, therefore it is the most unbiased. with some large positive or negative value which it may mean there are underestimating or overestimating the Apple's open stock price for the next 5 month.
