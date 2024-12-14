# Taxi price regression

In here, I use [this](https://www.kaggle.com/datasets/denkuznetz/taxi-price-prediction) to construct a model of linear regression. 

In ```notebooks/eda.ipynb```, I engaged in exploratory data analysis of the dataset.

In ```notebooks/regression.ipynb```, I constructed a regression model of the data set. 

The model I have constructed is the regression equation

$y = -1.886811 y_{TimeOfDayAfternoon} - 2.977867 y_{TimeOfDayEvening} - 2.236602 y_{TimeOfDayMorning} - 3.265308 y_{TimeOfDayNight} - 1.787519 y_{DayOfWeekWeekday} - 1.861816 y_{DayOfWeekWeekend} - 2.341083 y_{TrafficConditionsHigh} - 2.255336 y_{TrafficConditionsLow} - 2.442432 y_{TrafficConditionsMedium} + 1.265286 y_{WeatherClear} + 1.204347 y_{WeatherRain} + 5.895151 y_{WeatherSnow} + 0.936819 y_{BaseFare} + 24.192633 y_{PerKmRate} + 57.727301 y_{PerMinuteRate} + 0.302297 y_{TripDurationMinutes} + 1.677901 y_{TripDistancekm}$