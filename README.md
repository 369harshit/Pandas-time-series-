# Pandas-time-series-

***About 2,72,00,000 results (0.37 seconds) 
Time series data is a sequence of data points in chronological order that is used by businesses to analyze past data and make future predictions. These data points are a set of observations at specified times and equal intervals, typically with a datetime index and corresponding value.***

Step-1: Date Time index:  A DatetimeIndex is used to provide indexing for pandas Series and DataFrame s and works just like other Index types, but provides special functionality for time series operations. We'll cover the common functionality with other Index types first, then talk about the basics of partial string indexing.

Step-2: Rolling and Expanding : [1]Expanding window-Expanding window operations involve gradually including more data points as the window "expands" through the time series. This is useful for calculating cumulative metrics, such as cumulative sums or averages, considering all data points up to a given point in time.

[2]Rolling Window-Rolling window operations involve calculating metrics for a specified window of data that "rolls" or moves through the time series. This is particularly useful for smoothing out fluctuations and identifying trends or patterns over a specific time period.

Step-3: Time Resampling- Resampling is the process of changing the frequency of time series data. This involves either upsampling (increasing the frequency) or downsampling (decreasing the frequency) of the data. Resampling is commonly used in time series analysis to aggregate or interpolate data to a different time frequency. The resample method in pandas is a powerful tool for performing these operations.

Step-4: Time shifting- Time shifting refers to the operation of moving data points backward or forward along the time axis. This can be useful for various purposes, such as creating lag features, aligning datasets, or comparing time series at different points in time. The shift method in pandas is commonly used for time shifting.

