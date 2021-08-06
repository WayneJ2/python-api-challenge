# PythonAPI-Challenge (WeatherPy/VacationPy Analysis)

## Part I - WeatherPy

### Purpose
To analyze the weather of over 500+ cities and to create regression visualizations on the data.

### Description
The **_[WeatherPyCode.ipynb](https://github.com/WayneJ2/python-api-challenge/blob/main/WeatherPy/WeatherPyCode.ipynb)_** file includes the code as well as the developed tables that show various linear regression charts listed in the _Table of Figures_ below.

### Data Files 
1. **_[City Weather Data CSV](https://github.com/WayneJ2/python-api-challenge/blob/main/WeatherPy/city_weather.csv)_**

## List of Figures 
###### _(labels for charts unable to be shown correctly in Github)_

1. **[Northern Hemisphere - Temperature (F) vs. Latitude](https://github.com/WayneJ2/python-api-challenge/blob/main/WeatherPy/Images/NH_tempvslat.png)** _(Sample shown)_
    1.  ![Northern Hemisphere - Temperature (F) vs. Latitude](/WeatherPy/Images/NH_tempvslat.png)
3. **[Southern Hemisphere - Temperature (F) vs. Latitude](https://github.com/WayneJ2/python-api-challenge/blob/main/WeatherPy/Images/SH_tempvslat.png)**
4. **[Northern Hemisphere - Humidity (%) vs. Latitude](https://github.com/WayneJ2/python-api-challenge/blob/main/WeatherPy/Images/NH_humidityvslat.png)**
5. **[Southern Hemisphere - Humidity (%) vs. Latitude](https://github.com/WayneJ2/python-api-challenge/blob/main/WeatherPy/Images/SH_humidityvslat.png)**
6. **[Northern Hemisphere - Cloudiness (%) vs. Latitude](https://github.com/WayneJ2/python-api-challenge/blob/main/WeatherPy/Images/NH_cloudsvslat.png)**
7. **[Southern Hemisphere - Cloudiness (%) vs. Latitude](https://github.com/WayneJ2/python-api-challenge/blob/main/WeatherPy/Images/SH_cloudsvslat.png)**
8. **[Northern Hemisphere - Wind Speed (mph) vs. Latitude](https://github.com/WayneJ2/python-api-challenge/blob/main/WeatherPy/Images/NH_windsvslat.png)**
9. **[Southern Hemisphere - Wind Speed (mph) vs. Latitude](https://github.com/WayneJ2/python-api-challenge/blob/main/WeatherPy/Images/SH_windsvslat.png)**
10. **[Snippet of API request log](https://github.com/WayneJ2/python-api-challenge/blob/main/WeatherPy/Images/City_printlog.PNG)**

## Observable Trends From Data

1. 75% of the cities in the data have an avg temperature below 80 deg, humidities less than 85% and 93% cloudiness.
2. Temperatures follow expected pattern of being warmer the closer a city is to the equator.
3. Cloudiness, Humidity, and Wind Speed had little to no correlation to a city's position on latitude.

## Part II- VacationPy

### Purpose
To use weather data gathered from Part I to locate cities with ideal weather conditions and find the closest hotel to each coordinate.

### Description
The **_[VacationPyCode.ipynb](https://github.com/WayneJ2/python-api-challenge/blob/main/VacationPy/VacationPyCode.ipynb)_** file includes the code as well as the developed maps that show the humidity levels and closest hotel for each city.

### Data Files 
1. **_[Hotel Data CSV](https://github.com/WayneJ2/python-api-challenge/blob/main/VacationPy/Ideal_cities_hotel_list.csv)_**

## List of Figures

### Humidity Heatmap of Ideal Weather locations
![Heatmap1](/VacationPy/Images/Humidity_Heatmap.png)

### Combo Heatmap of closest hotel in Ideal locations
![Heatmap2](/VacationPy/Images/hotel_combo_map.PNG)

