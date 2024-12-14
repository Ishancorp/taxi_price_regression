# Taxi price regression

In here, I use [this](https://www.kaggle.com/datasets/denkuznetz/taxi-price-prediction) to construct a model of linear regression. 

In ```notebooks/eda.ipynb```, I engaged in exploratory data analysis of the dataset.

In ```notebooks/regression.ipynb```, I constructed a regression model of the data set. 

The model I have constructed is the regression equation

$y = -1.886811 x_{TimeOfDayAfternoon} - 2.977867 x_{TimeOfDayEvening} - 2.236602 x_{TimeOfDayMorning} - 3.265308 x_{TimeOfDayNight} - 1.787519 x_{DayOfWeekWeekday} - 1.861816 x_{DayOfWeekWeekend} - 2.341083 x_{TrafficConditionsHigh} - 2.255336 x_{TrafficConditionsLow} - 2.442432 x_{TrafficConditionsMedium} + 1.265286 x_{WeatherClear} + 1.204347 x_{WeatherRain} + 5.895151 x_{WeatherSnow} + 0.936819 x_{BaseFare} + 24.192633 x_{PerKmRate} + 57.727301 x_{PerMinuteRate} + 0.302297 x_{TripDurationMinutes} + 1.677901 x_{TripDistancekm}$