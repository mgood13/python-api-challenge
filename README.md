# python-api-challenge
## WeatherPy
> The WeatherPy module is intended to generate cities from a randomly generated
>list of latitude and longitude points uniformly distributed across the entire
>range of possible values. A weather check is performed on each of the cities
>to collect the city's Max Temperature, Humidity, Cloudiness, Wind Speed, country,
>and the current date. It then plots each of these data points relative to latitude
>for the entire world. It then re-plots each of the data points for each hemisphere
>to see if there are any further trends that can be observed in the data. It
>also prints the collected data to a csv file and finally saves all of the figures
>into a folder Images.

## VacationPy
> The VacationPy module takes the data from the the WeatherPy module to identify
>vacation spots. First it creates a heat map across the world based upon the 
>humidity. Next it is filters the entire list of cities based upon my personal
>preferences of each parameter (Temperature, Humidity, Cloudiness, Wind Speed, etc).
>It then uses the Google Places API to find the nearest hotel to each city that
>matches the laid out ideal weather criteria. Finally, it places markers on the
>created gmaps figure on top of the cities that matched the criteria along with 
>the name of the hotel there that was found (if there was one). When the pandemic is
>over I'm definitely taking a trip to New Zealand, it sounds nice there.