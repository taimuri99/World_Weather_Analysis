# World Weather Analysis
Module 6: World Weather Analysis using Jupyter Notebook & APIs.
## Deliverable 1

For deliverable 1, we created a new set of 2000 latitudes and longitudes and using citipy module, found the nearest cities. We performed an API call with OpenWeatherMap to get weather data for these cities and added the required data:

1) Latitude and Longitude
2) Maximum temperature
3) Percent humidity
4) Percent cloudiness
5) Wind speed
6) Weather description (for example, clouds, fog, light rain, clear sky)

This data was added to a dataframe which was exported as a csv file.

<img width="728" alt="Screenshot 2021-12-27 at 12 48 38" src="https://user-images.githubusercontent.com/87828174/147495988-c208ef1f-f8af-4e64-807f-ee634a09f864.png">

## Deliverable 2

In deliverable 2, we wrote two input statements that prompt the user to enter their weather preferences such as minimum and maximum temperature criteria for their vacation. We use the loc method to filter the DataFrame for temperature criteria and then create a new DataFrame with this filtered data.

Using the supplied search parameters and after cleaning the data, the dataframe is iterated through while making an API call to find the nearest hotels according to the latitude and longitude and store them in assigned variables.

This was then plotted with a marker layer map with pop-up markers for the cities and saved as a png. Each marker has the following information:

- Hotel name
- City
- Country
- Current weather description with the maximum temperature

<img width="1374" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/87828174/147497457-d0ee9d3d-92bb-4ca4-a69c-9e1964b4b6e2.png">

## Deliverable 3
In deliverable 3, 4 cities are chosen which represent a travel map for a user. Using the loc method, dataframes are created for each city on the travel map:

1) Starting City
2) Ending City
3) Stop 1
4) Stop 2
5) Stop 3

The starting and ending city would be the same. A directions layer map between the cities and the travel map is created using the latitude and logitude pairs of these cities. 

<img width="1055" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/87828174/147497945-90d8ade2-afd1-41b5-aeaf-8c68b669c6ff.png">

A marker layer map with a pop-up marker for the cities on the itinerary is also created.

<img width="1306" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/87828174/147497973-c68221ae-01c7-4e4a-a3f5-e52b29be873f.png">

