# Lap Time Prediction of a Formula One Car
This project is aimed at predicting lap times of a formula one car based on driver, lap number, tyre compound, team and weather data.

# Data Collection and Preprocessing
Data is collected and updated using FastF1 python module as ErgastAPI is being deprecated at the end of this year.
For now, the data only contains lap times from race session held on Sundays as qualifying times have no impact on race lap times.
Data is split into 70/30 train/test ratio for now.

# Model Selection and Training
A Random Forest Regression model is selected for predictions as it tends to yield better results for time series forecasting.
As this project is a W.I.P, an LSTM will be used for better results in future.
