# Airline-Passengers-Time-series-analyais-ARIMA-vs-SARIMA

# Problem Statement
An airline company has the data of the number of passengers that have travelled with them on a particular route for the past few years. Using this data, they want to see if they can forecast the number of passengers for the next twelve months.

Making this forecast could be quite beneficial to the company as it would help them take some crucial decisions like -

-What capacity aircraft should they use?
-When should they fly?
-How many air hostesses and pilots do they need?
-How much food should they stock in their inventory?

1.Quantity: Number of passengers

2.Granularity: Flights from city A to city B; i.e., flights for a particular route

3.Frequency: Monthly

4.Horizon: 1 year (12 months)

A seasonal autoregressive integrated moving average (SARIMA) model is a time series modeling technique comprising of 4 features which are-

--Auto-Regressive: Takes the linear combination of past values of data to predict the next point in future.

--Moving Average: Takes linear combination of past forecast errors to predict the next point in future.

--Differencing: Transformation to make Time Series stationary.

--Seasonality: Repeated cycle

The SARIMA model combines all the above characterstics to make a forecast about future values of Time series data points. It is one of the most practically used statistical approaches to deal with Time series data.

![airline](https://user-images.githubusercontent.com/89026851/192047029-3cee046a-6364-4523-966a-aa443823aedb.png)
