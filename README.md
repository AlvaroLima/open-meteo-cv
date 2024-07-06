# Historical Weather data From Cabo Verde by Open Meteo Weather

Open-Meteo is an open-source weather API and offers free access for non-commercial use. No API key is required. You can use it immediately!

Head over to https://open-meteo.com! Stay up to date with our blog at https://openmeteo.substack.com.

---

This repository provides historical weather data from 11 localities in Cabo Verde, all the way back from 1940 to 2024. Each csv file provides temperature and rain data from a specific locality in Cabo Verde

## Data Sources
The Historical Weather API is based on reanalysis datasets and uses a combination of weather station, aircraft, buoy, radar, and satellite observations to create a comprehensive record of past weather conditions. These datasets are able to fill in gaps by using mathematical models to estimate the values of various weather variables. As a result, reanalysis datasets are able to provide detailed historical weather information for locations that may not have had weather stations nearby, such as rural areas or the open ocean.

The models for historical weather data use a spatial resolution of 9 km to resolve fine details close to coasts or complex mountain terrain. In general, a higher spatial resolution means that the data is more detailed and represents the weather conditions more accurately at smaller scales.

The ECMWF IFS dataset has been meticulously assembled by Open-Meteo using simulation runs at 0z and 12z, employing the most up-to-date version of IFS. This dataset offers the utmost resolution and precision in depicting historical weather conditions.

However, when studying climate change over decades, it is advisable to exclusively utilize ERA5 or ERA5-Land. This choice ensures data consistency and prevents unintentional alterations that could arise from the adoption of different weather model upgrades.

You can access data dating back to 1940 with a delay of 2 days. If you're looking for weather information from the previous day, our Forecast API offers the &past_days= feature for your convenience.
