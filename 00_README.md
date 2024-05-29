# Data cleaning and linear regression

This tutorial is designed to optimize data preparation for machine learning, with a specific focus on predicting bike traffic patterns based on weather conditions. It includes a summary of the learning goals, a specific section that outlines the necessary requirements for completing the tutorial, and a section on the recommended practices for Research Data Management (RDM).

By merging bike traffic and weather data from Open Data sources, we aim to ensure data integrity and consistency, rectify any errors, and enhance the dataset with additional values for improved accuracy.

The tutorial employs Linear Regression, a straightforward machine learning model, to make predictions based on the input data. The data is sourced from Ottawa’s bike count data and historical weather data. These datasets, which are already downloaded and available in the tutorial repository, are combined to create a comprehensive training dataset.

## Data sources

| Dataset      | Source    | Licence |
|:-------------|:----------|:--------|
| bike_counter.xlsx | [Open Ottawa](https://open.ottawa.ca/documents/bicycle-trip-counters/about)      | Open Data licence version 2.0 |
| en_climate_daily_ON_6106001_2019_P1D.csv | [Environment Canada](https://climate.weather.gc.ca/climate_data/daily_data_e.html?hlyRange=2011-12-14%7C2023-01-25&dlyRange=2011-12-15%7C2023-01-25&mlyRange=%7C&StationID=49568&Prov=ON&urlExtension=_e.html&searchType=stnName&optLimit=yearRange&StartYear=1840&EndYear=2023&selRowPerPage=25&Line=14&searchMethod=contains&txtStationName=ottawa&timeframe=2&time=LST&Day=25&Year=2019&Month=1#) | [Custom](https://climate.weather.gc.ca/prods_servs/attachment1_e.html) |
| en_climate_daily_ON_6106001_2020_P1D.csv | [Environment Canada](https://climate.weather.gc.ca/climate_data/daily_data_e.html?hlyRange=2011-12-14%7C2023-01-25&dlyRange=2011-12-15%7C2023-01-25&mlyRange=%7C&StationID=49568&Prov=ON&urlExtension=_e.html&searchType=stnName&optLimit=yearRange&StartYear=1840&EndYear=2023&selRowPerPage=25&Line=14&searchMethod=contains&txtStationName=ottawa&timeframe=2&time=LST&Day=25&Year=2020&Month=1#) | [Custom](https://climate.weather.gc.ca/prods_servs/attachment1_e.html) |
