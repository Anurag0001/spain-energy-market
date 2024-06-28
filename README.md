# spain-energy-market
# Machine Learning Applied to Forecasting: Daily Electricity Production in Spain 2014-2018

The main goal of this lab is to test whether a general and simple approach based on Machine Learning models, can yield good enough results in a complex forecasting problem.

Our objective is to test this methodology to perform 30-ahead daily forecast in electricity demand (Spanish market). It is a very complex time series given that the country is not in a stationary economic cycle (recovering from a economic recession) and industrial production is shifting towards tourism and a flourishing but yet quite small, industrial equipment and machine exportation sector. Despite this positive circumstances, both GDP increase and tourism gronwth rate have stopped going up.

This comes with changes in electricity consumption patterns that are also affected by energy efficiency improvements and changes in household consumption behavior.

In addition, some very deep regulation changes where carried out in the last few years (from 2013), that further impact in electricity market, but this impact is more notorious in price time series. Nonetheless, some changes in regulation have triggered a steady switch from regulated tariff to free-market tariff, where a smarter daily consumption profile is encouraged.

The methodology explained is aimed to be an experiment to demonstrate that even with a very simple, easy to implement approach, (but advanced in Machine Learning expertise) we can success in an advanced forecasting problem (long term daily forecasting, only two years of training data and a complex time series). The main profit to be achieved is to no longer rely on methods that require deep time series analysis and heavy statistical assumptions on data, such as ARIMA.


EDA Objectives:
* Is target variable normal with constant volatility
* Is there a seasonal pattern
* Is there a trend pattern

Model building objectives:
* Train a Machine Learning model being able to forecast (predict on future data) 30 periods ahead
* Feature Engineering process is automatic and no assumptions on data statistical properties is required 
* Assessment will be carried out computing MAPE (Mean Absolute Percent Error) for each forecating horizong on a holdout dataset

$$ MAPE =\frac{1}{N} \sum_{i=1}^{N}\frac{|y-\hat{y}|}{y}$$
