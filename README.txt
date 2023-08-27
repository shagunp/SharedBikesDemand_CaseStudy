# Predicting demand for shared bikes for BoomBikes
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. The requirement is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- BoomBikes wants to understand the factors affecting the demand for the shared bikes in the American market The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
- The dataset being used is day.csv which has the following fields:
    - instant: record index
    - dteday : date
    - season : season (1:spring, 2:summer, 3:fall, 4:winter)
    - yr : year (0: 2018, 1:2019)
    - mnth : month ( 1 to 12)
    - holiday : weather day is a holiday or not
    - weekday : day of the week
    - workingday : if day is neither weekend nor holiday is 1, else 0
    - weathersit 
    - temp : temperature in Celsius
    - atemp: feeling temperature in Celsius
    - hum: humidity
    - windspeed: wind speed
    - casual: count of casual users
    - registered: count of registered users
    - cnt: count of total rental bikes


## Conclusions
The following are the significant variables affecting demand for shared bikes after analysing the p values, VIF values and coefficients of variables.
- Year 
- Holiday
- Temperature
- Wind speed
- Seasons
- Weathersit
- Saturday 

## Contact
Created by [@shagunp] - feel free to contact me!



