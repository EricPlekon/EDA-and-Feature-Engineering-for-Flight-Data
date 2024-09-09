# EDA-and-Feature-Engineering-for-Flight-Data

This repository contains a Jupyter Notebook that performs Exploratory Data Analysis (EDA) and feature engineering based on a flight dataset.The goal is to clean the data, create new features, and prepare it for future machine learning tasks.


# Dataset
This dataset contains informaiton about various flights including the following:

- Airline: Name of airline
- Source: Source city of flight
- Destination: Destination city of flight
- Route: Route taken by flight
- Dep_Time: Departure time of flight
- Arrival_Time: Arrival time of flight
- Duration: Duration of flight
- Total_Stops: number of stops in flight route
- Additional_Info: Additional information about flight
- Price: Ticket price for flight
- Date, month, year: Date of the flight

# Analysis (Steps)

1. Data Cleaning: convert time-related columns (Arrival_Time, Dep_Time) to more usable formats (separate hours and mins), also drop unnecessary columns

2. Feature Engineering: Extract meaningful information from existing features, such as breaking down the Arrival_Time into Arrival_hour and Arrival_Min. Also, handled missing values.

3. Exploration: Check unique values in categorical columns such as Airline, Source, Additional_Info to better understand the data

# Requirements
These are the packages I used below
- Pandas
- Numpy
- Matplotlib
