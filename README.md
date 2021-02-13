# Forecasting Stocks and Market With Machine Learning

The best estimation ways of buying-selling time for a particular stock exchange were researched and analyzed. Different approaches were applied to the problem. Artificial intelligence can predict future predictions better than done. Therefore, it was thought that the prediction of disaggregated data may show stronger and more accurate estimates than using all data. However, better mathematical modeling such as regression makes this easier. It was decided to use LSTM, which would be useful to predict the trend, which is a component of the data. Meanwhile, it is possible to train the data in the long term and to see possible results with low error rate. Then it was aimed to reach the best working system. Based on the studies, the estimate was combined with Machine Learning and the trend estimate LSTM to get the prediction of all time series. 

# Usage of Libraries

![alt text](https://github.com/abidinzzeynel/Forecasting-Stocks-and-Market-With-Machine-Learning/blob/main/libraries.png)

# Result

This study has presented the extensive procedure of LSTM model for long term and short term stock price prediction based on close prices. LSTM neural network was used for both long term prediction model and sort term prediction model. In this study, APPLE stock share was selected to train and get high accuracy rate for long term prediction and BITCOIN stock share was selected to train and get high accuracy rate for short term prediction by various modeling. 

Long term prediction of stock price requires large data sets. Because the main idea for training the dataset is examine the trends of limited dataset if it is increasing or decreasing. Linear regression is a good technical way to calculate the slopes of specific range of dataset. So this long term prediction model calculates all slopes for specific range of dataset and train the data by LSTM neural network and it gives us a great opportunity to see if the trend of the data will increase or decrease.

Sort term prediction of stock price doesn’t need very large data as long term prediction. The main idea is similar to long term prediction but this model trains the close prices of stock shares by LSTM neural network. After training of the dataset the objective way to control the accuracy rate is compare it to next day’s open prices. This models accuracy rate is not as much as the other model but it satisfies the most of the predictions. 

That can be said this study shows us predicting the stock shares is possible but there are too many factors that cause fluctuation of the stock market. Most of them can not predictable at all. For now our models just based on the numbers and mathematical calculations but in the future projects the economical parameters can be include the neural system.
