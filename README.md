# NYC TLC Trip Record Data Analysis

This repository contains a comprehensive analysis of the **New York City Taxi and Limousine Commission (TLC) Trip Record** dataset. The dataset includes detailed records of yellow taxi trips in New York City, and the analysis covers various aspects of the trips, such as trip durations, pickup and drop-off locations, fare amounts, and more.

## Overview

This repository provides a Jupyter notebook (.ipynb file) used to analyze and visualize the **NYC TLC Trip Record** dataset. The main objective of this analysis is to uncover insights about taxi trip patterns, identify trends, and explore factors influencing trip durations, fare amounts, and other key metrics. This repository also demonstrates techniques for cleaning, transforming, and visualizing large datasets.

## **Problem Statement**

1. Understanding the distribution of Variables such as trip duration, distance, passenger count,fare and tip amount
2. Identifying total trips count of each Vendor: Examining if the distribution of trips are balanced between vendors
3. Evaluating Payment Methods: Identifying preferred payment methods
4. Analyzing high-traffic time and location: Identifying distribution of trips within a day, a week, and Pick-up zone

## Dataset Description

The NYC TLC Trip Record dataset includes the following columns:
- **pickup_datetime**: Date and time when the trip started.
- **dropoff_datetime**: Date and time when the trip ended.
- **pickup_location**: Latitude and longitude of the pickup location.
- **dropoff_location**: Latitude and longitude of the drop-off location.
- **trip_distance**: Distance of the trip in miles.
- **fare_amount**: The total fare charged to the passenger.
- **passenger_count**: Number of passengers in the taxi.
- **payment_type**: Payment method used (e.g., credit card, cash).
- **trip_type**: Type of trip (e.g., street-hail, dispatched).
- **ehail_fee**: The fee for trips hailed via e-hailing apps

### Downloading the Data

The dataset can be downloaded from Kaggle
## Data Analysis

The analysis consists of multiple steps:

1. **Data Cleaning**:
   - Handling missing values and outliers.
   - Converting data types (e.g., datetime conversion)
   
2. **Exploratory Data Analysis (EDA)**:
   - Descriptive statistics and data distributions.
   - Visualizations to understand trip patterns (e.g., number of trips per day, peak hours, trip duration distribution).

3. **Key Metrics**:
   - Average trip fare by trip type.
   - Comparison of street-hail vs. dispatched trips.
   - Correlations between trip duration, fare, distance, and other variables.

4. **Outlier Detection**:
   - Identifying outliers in trip duration, fare, and distance.
   - Investigating unusual patterns in the data.

5. **Geospatial Analysis**:
   - Mapping pickup and drop-off locations using **geospatial data**.
   - Heatmaps showing high-traffic areas in NYC.

## Key Findings

Here are some of the key insights derived from the analysis:

- **Street-Hailed vs. Dispatched Trips**: The majority of trips were street-hailed, with dispatched trips making up a significantly smaller portion.
- **Peak Hours**: The most trips occurred during office hours, with a noticeable dip a few hours after office hours end.
- **Payment Type**: The majority of trip payments were made in credit cards.

To run the analysis, simply open the Jupyter notebook file in your preferred environment (e.g., Jupyter Notebook, JupyterLab).

---

Feel free to reach out if you have any questions or need further assistance with the analysis. Happy coding!

