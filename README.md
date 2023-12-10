# Python API Challenge

## WeatherPy

The weather data is consumed from [OpenWeatherMap API](https://openweathermap.org/api).\ 
A sample of ~600 cities is randomly selected with following ranges for latitude(-90, 90) and longitude (-180, 180).
Various scatter plots are drawn to compare the relationship between latitude vs Temparature, Humidity, Cloudiness & Wind Speed.\
Various Linear Regression Plots are drawn to compare the weather pattern between Nothern Hemisphere (latitude  > 0) and Southern Hemishpere (latitude >= 0)

## VacationPy

The restaurant data is consumed from [Geoapify API](https://apidocs.geoapify.com/).\
A hotel map is drawn for cities filtered for ideal weather condition (Max temp > 18 and Max Temp < 24 and Wind Speed < 5).

## Files
* Source Code -\
  WeatherPy/WeatherPy.ipynb\
  VacationPy/VacationPy.ipynb
* Config -
  config/api_keys.py
* APIs -
  [OpenWeatherMap API](http://api.openweathermap.org/data/2.5/weather)
  [Geoapify API](https://api.geoapify.com/v2/places)
* Output -\
  output_data/cities.csv\
  output_data/Fig1.png\
  output_data/Fig2.png\
  output_data/Fig3.png\
  output_data/Fig4.png
  
## Run Instructions
* Obtain API keys for OpenWeather Map & Geoapify APIs
* Open a terminal
* Confirm condo version\
  conda --version
* Confirm jupyter version\
  jupyter --version
* Activate conda environment\
  conda activate dev
* Launch Jupyter Notebook\
  jupyter notebook
* Jupyter Notebook is opened in a browser
* Copy config/api_keys.py.template to config/api_keys.py
* Update config/api_keys.py with API keys for OpenWeather Map & Geoapify APIs
* Open "WeatherPy/WeatherPy.ipynb" file using Jupyter Notebook
* Click on 'Cell > Run All' to run
* Open "VacationPy/VacationPy.ipynb" file using Jupyter Notebook
* Click on 'Cell > Run All' to run
