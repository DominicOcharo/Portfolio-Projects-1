# Delhi Climate Analysis

## Introduction

This project analyzes daily climate time series data from Delhi to gain insights into temperature, humidity, wind speed, and mean pressure over several years. The dataset used in this analysis is sourced from [Kaggle](https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data).

## Getting Started

To run this project, make sure you have Python installed on your machine along with the following libraries:

- pandas
- matplotlib
- seaborn

You can install these libraries using pip:

```
pip install pandas matplotlib seaborn
```

After installing the required libraries, clone this repository to your local machine and run the provided Python script.

## Dataset

The dataset used in this project is located at [this link](https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data). It contains daily climate data for Delhi, including the following columns:

1. `date`: Date of the observation
2. `meantemp`: Mean temperature for the day
3. `humidity`: Humidity percentage
4. `wind_speed`: Wind speed in km/h
5. `meanpressure`: Mean pressure in hPa

## Analysis

### 1. Overview of the Data

The `delhi_weather_data` function provides a summary of the dataset, including descriptive statistics and data types.

### 2. Mean Temperature Over the Years

The `mean_temp_vs_year` function visualizes the mean temperature in Delhi over multiple years.

### 3. Humidity Over the Years

The `humidity_vs_year` function displays the humidity levels in Delhi over the years.

### 4. Wind Speed Over the Years

The `wind_speed_vs_year` function illustrates the wind speed patterns in Delhi over the years.

### 5. Relationship Between Temperature and Humidity

The `temperature_vs_humidity` function presents the relationship between temperature and humidity using a scatter plot.

### 6. Temperature Change Over the Years

The `temp_change_in_years` function demonstrates the temperature change in Delhi over the years, categorized by month.

## Conclusion

This project provides valuable insights into the climate trends in Delhi over the analyzed period. By visualizing temperature, humidity, and wind speed data, contributes to a better understanding of the local climate patterns. Further analysis and interpretation of the data can lead to informed decisions in various sectors, including agriculture, urban planning, and environmental management.
