# python-api-challenge
homework6

The Python code randomly selects a group of 500+ cities in the world. Then, the code collects data from the OpenWeatherMap API to create a representatitve model of weather across world cities. The API data is used to graph the following relationships:
Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

conclusions:
Temperature shas a positive correlation with latitude
As expected, the weather gets warmer as one approaches the equator (0 Deg. Latitude). 
There is weak linear relationship between latitude and cloudiness. 
Windspeed vs lat --strong positive linear relationship in the northern data. Strong negative linear relationship in the southern data.
Humidity vs lat - as lat increases, humidity increases. Strong linear relationship

Files
A "WeatherPy.ipynb" Jupyter Notebook that contains the Python code for the analysis
A "VacationPy.ipynb" Jupyter Notebook that contains the Python code for the analysis
A "api_keys.py" with geoapify and weather api keys
citites.csv
Four PNG files of the visuals
