# python-api-challenge

This challenge had two parts.  The first part was to use the OpenWeatherMap API to create a DataFrame of 
at least 500 random cities from around the world.  After finding the cities, several scatter plots and regressions were created
to show the relationship between latitude and different weather conditions.  These plots include:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

The second part of the challenge was to use the csv created from the DataFrame in part 1 and Google Places API
to locate cities with what I consider my ideal vacation conditions.  Then using those ideal conditions, use the API
to locate hotels within 5000m of the returned coordinates.