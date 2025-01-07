# Timeseries_Food-Demand-Forecasting
This project is a continuation of the research paper titled "Time Series Forecasting and Modeling of Food Demand Supply Chain Based on Regressors Analysis" by Sandeep Kumar Panda and Sachi Nandan Mohanty. The projecy builds upon their findings, aiming to enhance food demand forecasting using Temporal Convolutional Networks (TCN).


Dataset:
The dataset used in this project is the Genpact Food Demand Dataset, which contains historical data on food orders from various centers. Data preprocessing has been performed, and the processed dataset is included in the provided zip files. Feature engineering was also conducted to create additional features, including one-hot encoding for categorical variables, rolling statistics(mean and standard deviation) for historical order counts, and lag features to capture temporal dependencies.



Modeling:  Temporal Convolutional Networks (TCN)
In this project,Temporal Convolutional Network (TCN) was employed for predicting food demand. TCNs are effective for modeling sequential data, making them ideal for time series forecasting tasks. The TCN model was trained and validated on the data from weeks 1 to 120, and then tested for weekly food demand forecasting for 25 weeks from week 121 to 145. Graphs were plotted to visualize the actual versus predicted weekly orders, providing insights into the model's performance and accuracy in forecasting food demand.


