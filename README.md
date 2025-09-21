[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MCy_CicX)
# 911 Calls Data Task

This repository contains solutions for an Exploratory Data Analysis (EDA) task involving 911 call data. The dataset, sourced from [Kaggle](https://www.kaggle.com/mchirico/montcoalert), provides insights into emergency call records with features including geolocation, timestamps, and emergency types.

## Dataset Description

The dataset includes the following fields:
- **lat**: Latitude (string)
- **lng**: Longitude (string)
- **desc**: Emergency call description (string)
- **zip**: Zip code (string)
- **title**: Emergency title/category (string)
- **timeStamp**: Timestamp in `YYYY-MM-DD HH:MM:SS` format (string)
- **twp**: Township (string)
- **addr**: Address (string)
- **e**: Dummy variable (always `1`)

## Objectives

The EDA task aims to:
1. Investigate basic data properties, such as missing values and data types.
2. Explore trends and distributions of 911 call data.
3. Visualize patterns across time and space to uncover insights into emergency responses.

## Instructions

1. **Data Import**:
   - Import necessary libraries (e.g., `numpy`, `pandas`, `matplotlib`).
   - Load the dataset into a DataFrame.
   
2. **Basic Analysis**:
   - Display basic information using `info()` and preview the data with `head()`.
   - Identify top zip codes and townships for 911 calls.
   
3. **Data Visualization**:
   - Use plots to examine:
     - Distribution of emergency categories.
     - Call frequency trends over time.
     - Geographical patterns using latitude and longitude.
     
4. **Insights**:
   - Provide a narrative on observed patterns and anomalies.


## Acknowledgements

- Dataset by [Kaggle](https://www.kaggle.com/mchirico/montcoalert)