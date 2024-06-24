# London Bicycle Rides
Project idea from [Mo Chen](https://www.youtube.com/@mo-chen)

## Tools Used for this Project
- Python: [Python Code Link](https://github.com/colinryanx/London-Bicycle-Rides/blob/main/Python%20Project%20-%20London%20Bicycle%20Rides.ipynb)
- Tableau: [Dashboard Link](https://public.tableau.com/app/profile/colin.ryan.subido/viz/London_Bikes_Project_17187842296680/LondonBikeRides)
![London Bike Rides](https://github.com/colinryanx/London-Bicycle-Rides/assets/171652558/220984f1-4660-4415-9968-4888b58524c1)

## Problem Statement
City planners and transportation agencies are increasingly promoting bicycle usage as a sustainable mode of transportation in London. However, without a clear understanding of usage patterns and trends, it is challenging to optimize infrastructure, allocate resources efficiently, and develop strategies to encourage more people to use bicycles. There is a need for a comprehensive analysis of London's bicycle ride data from 2015 to 2016 to identify usage trends and understand the factors influencing bicycle rides.

## Objective
The purpose is to analyze and visualize the trend of bicycle rides from 2015 to 2016. This analysis aims to:
- Identify patterns and fluctuations in bicycle usage over the two-year period.
- Determine peak and off-peak times for bicycle rides on a daily, weekly, and monthly basis.
- Analyze the impact of external factors such as weather conditions, public holidays, and special events on bicycle ride trends.
  
By visualizing these trends, the goal is to support city planners, transportation agencies, and bike-sharing companies in making data-driven decisions to optimize bicycle infrastructure, enhance service offerings, and promote sustainable transportation.

## Metadata:
- **timestamp** - timestamp field for grouping the data
- **cnt** - the count of a new bike shares
- **t1** - real temperature in C
- **t2** - temperature in C "feels like"
- **hum** - humidity in percentage
- **wind_speed** - wind speed in km/h
- **weather_code** - category of the weather
- **is_holiday** - boolean field - 1 holiday / 0 non holiday
- **is_weekend** - boolean field - 1 if the day is weekend
- **season** - category field meteorological seasons: 0-spring ; 1-summer; 2-fall; 3-winter.

"weather_code" category description:
1 = Clear ; mostly clear but have some values with haze/fog/patches of fog/ fog in vicinity 2 = scattered clouds / few clouds 3 = Broken clouds 4 = Cloudy 7 = Rain/ light Rain shower/ Light rain 10 = rain with thunderstorm 26 = snowfall 94 = Freezing Fog


(_[Dataset Source](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset/data)_)
