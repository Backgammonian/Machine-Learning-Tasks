# Time series forecasting

The main goal of these projects is to learn about forecasting techniques upon time series.\
The difference between regression analysis and time series forecasting is the ordering of data along the time axis.\
It means that ML & DL algorithms should learn not just patterns from the data but also trends, seasonality and cyclicity of time series.

## Weather temperature prediction

An attempt to predict weather temperature using its historical values and seasonality.\
The dataset is provided by [https://www.kaggle.com/datasets/muthuj7/weather-dataset](https://www.kaggle.com/datasets/muthuj7/weather-dataset) from Kaggle.

The key steps of the project:
* Dataset lookup & visual analysis
* Autocorrelation & partial autocorrelation charts
* Preprocessing (index sorting, filling missing values)
* Time features engineering
* Cross-validation for time series on ML models and neural networks (including NNs with recurrent layers)

Main conclusions:
* Ensembles & neural networks perform very well on this dataset (in regards to (R)MSE, MAE, R2 metrics)
* I've noticed that dummy regressor (basically just a straight line) gives the best MAPE result compared to the rest of models what is kind of strange

![weather_mse](weather_mse.png)
![weather_mape](weather_mape.png)

## Hourly energy consumption prediction
