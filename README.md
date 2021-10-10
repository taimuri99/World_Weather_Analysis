# World Weather Analysis
For deliverable 1, we created a new set of 2000 latitudes and longitudes and using citipy module, found the nearest cities. We performed an API call to get weather data for these cities from OpenWeather and added the required data:

1) Latitude and Longitude
2) Maximum temperature
3) Percent humidity
4) Percent cloudiness
5) Wind speed
6) Weather description (for example, clouds, fog, light rain, clear sky)

In deliverable 2, we filtered the dataframe to match the user input of maximum and minimum temperatures they would like. This was a new dataframe and was iterated through while making an API call to find the nearest hotels. This was then plotted with a marker layer map with pop-up markers for the cities and saved as a png.

In deliverable 3, 4 cities are chosen which represent a travel map for a user:

1) Starting City
2) Ending City
3) Stop 1
4) Stop 2
5) Stop 3

The starting and ending city would be the same. A directions layer map between the cities and the travel map is created. A marker layer map with a pop-up marker for the cities on the itinerary is also created.

