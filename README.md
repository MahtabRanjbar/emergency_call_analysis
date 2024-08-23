 # 911 Emergency Calls Data Analysis
## Project Overview
This project analyzes 911 emergency call data from Montgomery County, PA. The goal is to uncover insights about emergency types, patterns, and trends using data science techniques. The project includes data preprocessing, exploratory data analysis (EDA), clustering, time series forecasting, and classification modeling.

## Key Objectives:
1. **Understand Patterns in 911 Calls:** Investigate when, where, and what types of emergencies occur most frequently.
2. **Geographical Hotspots Analysis:** Identify regions with the highest call density using clustering techniques.
3. **Forecast Emergency Call Trends:** Use time series models to predict future call volumes.
4. **Predict Emergency Type:** Build a classification model to predict the type of emergency based on key features like time, location, and day.

## Project Structure
- Data Loading and Preprocessing:

Data was cleaned, and new features such as Hour, Day of Week, and Month were created from the timeStamp.
The emergency type (Category) was extracted from the title column.

- Exploratory Data Analysis (EDA):

Visualized the distribution of emergency types.
Analyzed call trends across different days, months, and hours.
Created heatmaps to explore call volume variations.

- Clustering Analysis:

Applied K-means clustering on the geographical data (latitude and longitude) to identify emergency hotspots.

- Time Series Forecasting:

Implemented ARIMA to forecast future emergency call volumes.

- Classification Model:

Built a Random Forest classifier to predict the emergency type based on time and location features.
