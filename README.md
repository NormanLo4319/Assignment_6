# What's the Weather Like?

## Background

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. So we are using Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

Now, we know what you may be thinking: _"Duh. It gets hotter..."_

But, if pressed, how would you **prove** it?

## WeatherPy

In this challenge, we create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, we utilized a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

The objective is to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

The final notebook:

* Randomly select 500 unique (non-repeat) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls.
* Include a print log of each city as it's being processed with the city number and city name.
* Save both a CSV of all data retrieved and png images for each scatter plot.

![Weather](Images/Cloudiness.png)

![Weather](Images/Humidity.png)

![Weather](Images/Max_Temp.png)

![Weather](Images/Wind Speed.png)

Note:

* This analysis is completed using a Jupyter notebook.
* We use the Matplotlib or Pandas plotting libraries.
* We include a written description of three observable trends based on the data.



