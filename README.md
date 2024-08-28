United States Airlines Analysis
Project Overview
Frequent flight delays have been a significant concern for air travelers, contributing to a large proportion of consumer complaints. This project aims to identify the factors contributing to avoidable flight delays and develop a predictive model to determine if a flight will be delayed. By analyzing flight, airport, and runway data, we seek to improve the understanding of delay patterns and help airlines mitigate these issues.

Objectives
Data Aggregation: Collect and aggregate data related to flights, airports, and runways to identify potential causes of avoidable delays.
Exploratory Data Analysis (EDA): Perform data visualization and statistical analysis to uncover insights regarding flight delays.
Predictive Modeling: Build machine learning models to predict flight delays and compare the performance of various models.
Hypothesis Testing: Test hypotheses regarding the impact of airport altitude, the number of runways, and flight duration on delays.
Dashboard Creation: Develop a Tableau dashboard to visualize key findings and enhance data storytelling.
Datasets
The project uses the following datasets:

Airlines.xlsx: Contains data on flights, including flight number, airline, aircraft type, source and destination airports, day of the week, departure time, flight duration, and delay status.
Airports.xlsx: Provides information about airports, such as type, location, elevation, continent, country, region, and whether the airport has scheduled services.
Runways.xlsx: Details runway characteristics, including length, width, surface type, lighting, and elevation of runway ends.
Key Variables
Flight Data: id, Airline, Flight, AirportFrom, AirportTo, DayOfWeek, Time, Length, Delay
Airport Data: id, type, name, latitude_deg, longitude_deg, elevation_ft, continent, iso_country, iso_region, municipality, scheduled_service, gps_code, iata_code, local_code
Runway Data: id, airport_ref, airport_ident, length_ft, width_ft, surface, lighted, closed, le_ident, le_latitude_deg, le_longitude_deg, le_elevation_ft, le_heading_degT, le_displaced_threshold_ft, he_ident, he_latitude_deg, he_longitude_deg, he_elevation_ft, he_heading_degT, he_displaced_threshold_ft
Project Tasks
Week 1
Data Collection:
Import and aggregate data related to flights, airports, and runways.
Identify and join key datasets to create a comprehensive dataset.
Missing Value Treatment:
Examine and handle missing values in the dataset, justifying the chosen methods.
Data Visualization:
Compare delay rates among different airlines.
Analyze delays across different days of the week to identify safer travel days.
Visualize patterns in departure times and the impact of hub size on delays.
Hypothesis Testing:
Test the influence of airport altitude, runway availability, and flight duration on delays.
Use appropriate statistical methods to validate or reject these hypotheses.
Correlation Analysis:
Generate a correlation matrix for flight delay predictors and visualize it using a heatmap.
Week 2
Machine Learning:
Encode categorical variables using OneHotEncoder and OrdinalEncoder.
Split data into training and testing sets, standardize the data, and build logistic regression and decision tree models.
Evaluate model performance using accuracy metrics and handle overfitting.
Build and validate models using Gradient Boosting and compare results across different algorithms.
SQL Analysis:
Perform SQL queries to analyze delays across different days, airlines, and airport characteristics.
Identify patterns in delays at airports with specific features (e.g., number of runways, elevation).
Tableau Dashboard:
Create a Tableau dashboard to visualize key insights, with an emphasis on effective data storytelling.
Tools and Technologies
Programming Languages: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
Data Visualization: Tableau
Database Management: SQL
Conclusion
This project provides a comprehensive analysis of flight delays in the United States, identifying key factors contributing to delays and developing predictive models to improve on-time performance. The insights derived from this analysis will be valuable for airlines seeking to enhance operational efficiency and customer satisfaction.
