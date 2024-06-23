# Daily Parameter Definition
Aggregations are a simple 24 hour aggregation from hourly values. The parameter &daily= accepts the following values:

| Variable                          | Unit                           | Description                                                                                                                                                         |
|-----------------------------------|--------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| weather_code                      | WMO code                       | The most severe weather condition on a given day                                                                                                                     |
| temperature_2m_max                | °C (°F)                        | Maximum daily air temperature at 2 meters above ground                                                                                                               |
| temperature_2m_min                | °C (°F)                        | Minimum daily air temperature at 2 meters above ground                                                                                                               |
| apparent_temperature_max          | °C (°F)                        | Maximum daily apparent temperature                                                                                                                                   |
| apparent_temperature_min          | °C (°F)                        | Minimum daily apparent temperature                                                                                                                                   |
| precipitation_sum                 | mm                             | Sum of daily precipitation (including rain, showers, and snowfall)                                                                                                   |
| rain_sum                          | mm                             | Sum of daily rain                                                                                                                                                    |
| snowfall_sum                      | cm                             | Sum of daily snowfall                                                                                                                                               |
| precipitation_hours               | hours                          | The number of hours with rain                                                                                                                                        |
| sunrise                           | iso8601                        | Sun rise time                                                                                                                                                        |
| sunset                            | iso8601                        | Sun set time                                                                                                                                                         |
| sunshine_duration                 | seconds                        | Number of seconds of sunshine per day, determined by calculating direct normalized irradiance exceeding 120 W/m², following the WMO definition. Consistently less than daylight duration due to dawn and dusk. |
| daylight_duration                 | seconds                        | Number of seconds of daylight per day                                                                                                                                |
| wind_speed_10m_max                | km/h (mph, m/s, knots)         | Maximum wind speed on a day                                                                                                                                          |
| wind_gusts_10m_max                | km/h (mph, m/s, knots)         | Maximum wind gusts on a day                                                                                                                                          |
| wind_direction_10m_dominant       | °                              | Dominant wind direction                                                                                                                                              |
| shortwave_radiation_sum           | MJ/m²                          | Sum of solar radiation on a given day in Megajoules                                                                                                                  |
| et0_fao_evapotranspiration        | mm                             | Daily sum of ET₀ Reference Evapotranspiration of a well-watered grass field                                                                                         |

# Acknowledgement

Zippenfenig, P. (2023). Open-Meteo.com Weather API [Computer software]. Zenodo. https://doi.org/10.5281/ZENODO.7970649

Hersbach, H., Bell, B., Berrisford, P., Biavati, G., Horányi, A., Muñoz Sabater, J., Nicolas, J., Peubey, C., Radu, R., Rozum, I., Schepers, D., Simmons, A., Soci, C., Dee, D., Thépaut, J-N. (2023). ERA5 hourly data on single levels from 1940 to present [Data set]. ECMWF. https://doi.org/10.24381/cds.adbb2d47

Muñoz Sabater, J. (2019). ERA5-Land hourly data from 2001 to present [Data set]. ECMWF. https://doi.org/10.24381/CDS.E2161BAC

Schimanke S., Ridal M., Le Moigne P., Berggren L., Undén P., Randriamampianina R., Andrea U., Bazile E., Bertelsen A., Brousseau P., Dahlgren P., Edvinsson L., El Said A., Glinton M., Hopsch S., Isaksson L., Mladek R., Olsson E., Verrelle A., Wang Z.Q. (2021). CERRA sub-daily regional reanalysis data for Europe on single levels from 1984 to present [Data set]. ECMWF. https://doi.org/10.24381/CDS.622A565A