# python-api-challenge

In this assignment, 500+ cities will be analyzed to determine the relationship between different weather variables and latitude. 

You will need two API keys to be able to run this code. To obtain you API keys, please visit the below sites, and sign up for an API key.
You will then need to save your keys under an api_keys.py file, between the quotes, as displayed below. 

OpenWeatherMap API Key: https://openweathermap.org/api

Geoapify API Key: https://myprojects.geoapify.com/login

weather_api_key = " "

geoapify_key = " "

# WeatherPy
WeatherPy will showcase the below relationships, with visuals and conclusions within the notebook:

- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

- Northern Hemisphere: Temperature vs. Latitude
- Southern Hemisphere: Temperature vs. Latitude
- Northern Hemisphere: Humidity vs. Latitude
- Southern Hemisphere: Humidity vs. Latitude
- Northern Hemisphere: Cloudiness vs. Latitude
- Southern Hemisphere: Cloudiness vs. Latitude
- Northern Hemisphere: Wind Speed vs. Latitude
- Southern Hemisphere: Wind Speed vs. Latitude

# VacationPy
VacationPy will first showcase the humidity for each city that was analyzed in  WeatherPy via a map visual. The data is then filtered to locate cities that would meet the below weather specifications for an ideal vacation: 
- Max temperature lower than 95 degrees F but higher than 80F
- Wind speed less than 4.5 m/s
- Zero cloudiness
- No preference on humidity

Please note that the temperature within the code is in Celcius. 

Once these specifications were implemented, the nearest hotel was located for each of the cities. The final result displayed these cities only, in the second map. 

# Tools
The tools used to complete this assignment are as follows: 
Jupyter Notebook, Matplotlib, Numpy, Pandas, Hvplot, Citypy and Scipy Stats.


Thank you! 
