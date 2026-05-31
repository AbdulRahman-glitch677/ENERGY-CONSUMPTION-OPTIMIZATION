# Energy Consumption Optimization Using Machine Learning

## Project Overview

This project predicts building electricity consumption using historical energy usage data, weather conditions, and building metadata from the Building Data Genome Project 2 dataset.

The objective is to analyze energy consumption patterns, identify important influencing factors, and develop a machine learning model that can support energy optimization strategies.


## Dataset

**Dataset:** Building Data Genome Project 2

Files Used:

* electricity_cleaned.csv
* weather.csv
* metadata.csv


## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Random Forest Regressor
* Kaggle Notebook


## Methodology

### Data Preprocessing

* Loaded electricity, weather, and metadata datasets
* Converted timestamps into datetime format
* Handled missing values
* Merged weather and building information
* Created time-based features

### Features Used

* Square Footage (sqft)
* Air Temperature
* Cloud Coverage
* Dew Temperature
* Wind Speed
* Hour
* Day
* Month
* Weekday

### Machine Learning Model

Random Forest Regressor


## Model Performance

| Metric   | Value  |
| -------- | ------ |
| MAE      | 6.744  |
| RMSE     | 10.960 |
| R² Score | 0.994  |

The model achieved high prediction accuracy and explained approximately 99.4% of the variance in electricity consumption.


## Feature Importance

| Feature        | Importance |
| -------------- | ---------- |
| sqft           | 0.966      |
| hour           | 0.014      |
| airTemperature | 0.006      |
| dewTemperature | 0.003      |
| weekday        | 0.003      |
| day            | 0.003      |
| month          | 0.003      |
| windSpeed      | 0.001      |

### Key Finding

Building size (square footage) was identified as the most influential factor affecting electricity consumption.


## Energy Optimization Recommendations

* Improve HVAC efficiency in large buildings.
* Monitor high-energy-consuming facilities regularly.
* Implement weather-aware energy management systems.
* Schedule heavy electrical loads during off-peak hours.
* Track building energy performance over time.


## Kaggle Notebook

View the complete notebook here:

**Kaggle Notebook:**
https://www.kaggle.com/code/sabdulrahman/energy-consumption-optimization


## Repository Contents

README.md

## Author

Syed Abdul Rahman

Bachelor of Engineering (Artificial Intelligence & Machine Learning)

Mini Project: Energy Consumption Optimization
