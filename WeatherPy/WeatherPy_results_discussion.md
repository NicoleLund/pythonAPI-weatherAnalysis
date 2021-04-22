# WeatherPy Discussion

The WeatherPy challenge collected weather observation data from around the world.  The following obersvations were drawn from the data I collected (WeatherPy_20210422_results.html) and the sample data (WeatherPy_with_sample_data.html) provided in the course assignment.

## Observation 1 - WeatherPy_20210422_data.html

I hypothesized that I would see a Maximum Temperature gradient from equatorial to polar latitudes because temperature is strongly influenced by solar irradiance.  As a result temperature will generally be correlated with Latitude.  

My final API query was run at ~4pm on 4/22/2021. The resulting dataset showed good correlations between Latitude and Maximum Temperature. This affirms my hypothesis.


## Observation 2 - WeatherPy_with_sample_data.html

The cities.csv data provided in the course assignment also shows a measurable Max Temperature gradient. The regression analysis shows that this data is slightly less correlated but also affirms my hypothesis.

## Observation 3 - Both datasets

The other observed weather conditions showed negligible correlation by the r-values associated with the data.  This makes sense because humidity, cloudiness and wind speed are impacted more by local geography and weather systems than by solar irradiance (aka Latitude). 