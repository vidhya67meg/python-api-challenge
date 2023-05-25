# python-api-challenge

For the first part of this challenge(WeatherPy) I generated a list of random cities with a range of latitude and longitude combination using citipy library. Then using API from OpenWeatherMap weather data for the cities list generated was retrieved. This data was converted to a dataframe and scatter plots were generated to determine if factors like Temperature, Humidity, Cloudiness and Wind speed has a relation to Latitude. Using Linear Regression it was found that only Temperature had a relation to Latitude.

For the second part of the challenge(VacationPy) the cities from previous part were used to determine vacation spots with desirable weather conditions and hotels near those places. After narrowing down the cities with desirable conditions, API from geoapify was used to determine the first hotel located within 10,000 metres of each city coordinates. Then using hvplot a map with city and hotel name was generated.
