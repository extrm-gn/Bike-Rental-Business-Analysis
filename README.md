# Bicycle Rental Business Analysis 🚴‍♂️🌍📊

## Overview 📝

This project aims to analyze factors influencing the prevalence of biking as the main form of transportation in different countries and identify suitable locations for a bicycle rental business.

### Objectives:

1. **Understand Discrepancies:**
   - Investigate biking trends and disparities among countries.

2. **Identify Suitable Locations:**
   - Determine countries and cities most suitable for opening a bicycle rental business.

3. **Create Predictive Model:**
   - Develop a model predicting ideal locations for a bicycle rental business.

## Data Overview

### Bicycle Dataset 🚲

- **Features:**
  - Date, Season, Year, Month, Holiday, Weekday, Workingday, Weather Situation, Temperature, Humidity, Windspeed, Casual Users, Registered Users, Total Users.

- **Exploration:**
  - Seasonal variations in bike usage.
  - Weather conditions influencing user behavior and bike usage.

### Weather Dataset 🌦️

- **Features:**
  - Region, Country, City, Date, Average Temperature.

- **Preprocessing:**
  - Handling outliers and creating a dataset with quarterly temperatures.

### Population Dataset 👥

- **Features:**
  - City, Latitude, Longitude, Country, Population.

- **Preprocessing:**
  - Merging population data with city and country temperature data.

### GDP per Capita Dataset 💰

- **Features:**
  - Country, GDP per Capita (current US$).

- **Preprocessing:**
  - Merging GDP data with city and country temperature and population data.

## Exploratory Data Analysis 📊

- **Monthly Users Analysis:**
  - Peaks in September, lowest in January.
  - Shown the correlation with temperature and weather conditions.

- **Seasonal Users Analysis:**
  - Spikes in summer and fall for both casual and registered users.
  - Weather conditions influencing seasonal trends.

- **Temperature and Seasonal Discrepancies:**
  - Temperature inconsistencies across categorized seasons.
  - Addressing the mismatch by using quarters or specific months for accurate representation.

## Recommendations and Next Steps 🚀

1. **Operational Timing:**
   - Consider operating during quarters 3, 2, and 4 for optimal user engagement based on temperature and historical user data.

2. **Geographical Targets:**
   - Focus on countries and cities where biking is more prevalent, considering factors like weather, population, and GDP per capita.

3. **Model Development:**
   - Create a predictive model using machine learning to identify ideal locations for a bicycle rental business.

4. **Continuous Analysis:**
   - Regularly update and refine the analysis with new data to adapt to changing trends and conditions.

## Predictive Analysis 📚

### 1. Data Exploration and Filtering 📊
   - Analyzing temperature data for suitable biking conditions.
   - Filtering out countries and cities based on temperature, GDP per capita, and population.

### 2. Visualization 📈
   - Count plot of the number of cities per country.
   - Bar plot of GDP per capita for qualified countries.
   - Bar plot of the most suitable cities for biking rental business.

### 3. Findings and Recommendations 🌐🔍
   - Identification of suitable countries (USA, Singapore, Australia).
   - Recommendations for opening bike rental businesses in specific cities.

### 4. Machine Learning 🤖
   - Introduction of a response variable for machine learning.
   - Exploration of temperature variability and binning.
   - Creation of a binary response variable indicating suitability.
   - Setting up a data pipeline and benchmarking for accuracy.

### 5. Logistic Regression and Random Forest Models 📉
   - Implementation and evaluation of logistic regression.
   - Implementation and tuning of a random forest classifier.

## Conclusion 🎉
The analysis provides insights into suitable locations for a bicycle rental business based on temperature, GDP per capita, and population. Machine learning models offer predictions for business suitability, aiding in decision-making for potential investors or entrepreneurs.
