# python-api-challenge

This assignment was a part of the homework for the UNC Chapel Hill Data Science Bootcamp. In it, we were required to create two files.

The first, WeatherPy, uses the citypy library to get a list of random cities. Then, using the OpenWeatherMap API, I retreived weather data from the list of random cities and created a new data frame. With that, I used matplotlib to create various graphs showing the relationship between latitudes and certain variables like temperature and humidity. Then, I separated out the data into northern and southern hemispheres, repeated the graphs, and performed linear regression to analyze the relationships. Some analysis of the relationships has been included in the file, and the graphs and data were output into a separate folder.

The second file, VacationPy, builds off of the list of cities from the first file. This data is input into a new map with the cities plotted with sizes depending on humidity. Then, I filtered the current data into a smaller subset based off of certain weather conditions. Next, I used the Geoapify API to search for hotels close to those cities. I then displayed all of this information on another map.
