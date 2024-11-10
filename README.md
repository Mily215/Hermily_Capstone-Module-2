# NYC TLC Trip Record Data Analysis

This repository contains a comprehensive analysis of the **New York City Taxi and Limousine Commission (TLC) Trip Record** dataset. The dataset includes detailed records of yellow taxi trips in New York City, and the analysis covers various aspects of the trips, such as trip durations, pickup and drop-off locations, fare amounts, and more.

## Overview

This repository provides a Jupyter notebook (.ipynb file) used to analyze and visualize the **NYC TLC Trip Record** dataset. The main objective of this analysis is to identify operational insights to improve productivity, optimize vehicle distributions, and managing operational hours by providing actionable insights based on the analysis result of current dataset.

## **Problem Statement**

1. Understanding the distribution of Variables such as trip duration, distance, passenger count,fare and tip amount.
2. Identifying total trips count of each Vendor: Examining if the distribution of trips are balanced between vendors.
3. Evaluating Payment Methods: Identifying preferred payment methods.
4. Analyzing high-traffic time and location: Identifying distribution of trips within a day, a week, and Pick-up zone.

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

The NYC TLC Trip Record dataset is accessed from the Kaggle website under the title NYC TLC Trip Record Data Repository. (https://www.kaggle.com/datasets/salikhussaini49/nyc-tlc-trip-record-data-repository)

## Data Analysis

The analysis consists of multiple steps:

1. **Data Cleaning**:
   - Handling missing values and outliers.
   - Converting data types (e.g., datetime conversion).
   - Handling Duplicate Date
   - Removing invalid Data
   
2. **Exploratory Data Analysis (EDA)**:
   - Descriptive statistics and data distributions testing with (Shapiro)
   - Data Visualizations to understand trip patterns (e.g., number of trips per day, peak hours, Revenue, etc.).

3. **Key Metrics**:
   - Average trip fare by trip type.
   - High-demand hours
   - Comparison of street-hail vs. dispatched trips.
   - Comparison of Payment types: Credit Card, Cash, etc.

## Key Findings

Here are some of the key insights derived from the analysis:
- **Total Trips of Vendors: One of the Vendors had significantly higher Trip activity comparing to the other one.
- **Street-Hailed vs. Dispatched Trips**: The majority of trips were street-hailed, with dispatched trips making up a significantly smaller portion.
- **Peak Hours**: The most trips occurred during office hours, with a noticeable dip a few hours after office hours end.
- **Payment Type**: The majority of trip payments were made in credit cards.


---

Feel free to reach out if you have any questions or need further assistance with the analysis.

Thank you!
