# API---Weather-Data

What is the weather like as we approach the equator? 

To answer this question using data I randomly selected 500 cities. Using the city latitude and longitude and the OpenWeatherMap API the following data was collected for each city:

Temperature (F)
Humidity (%)
Cloudiness (%)
Wind Speed (mph)

The data was then dispalyed in a Pandas table and then visualised in scatter plots against the latitude.

## Analysis
- The curve of the scatter plot indicates, as expected, that despite the time of year the cities on or near the equator are experiencing high temberatures. As the latitude of the cities moves away from the equator whether it is to the north or to the south the temperatures start to fall (getting colder). While the cities were picked at random it is interesting to see that more cities north of the equator were picked compared to cities south of the equator. Could theis be becasue there are fewer cities south of the equator than north of the equator.
- There is no decipherable relationship between latitude and cloudiness and latitude and humidity. While there is a scientific way to measure humidity (%) I would be interested in how the % in cloudiness is measured.
- While there is no significant relationship between wind speed and latitude on this one day there could be other factors contributing to the low wind speeds on January 13, 2019.

