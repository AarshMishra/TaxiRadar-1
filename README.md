# TaxiRadar

**TaxiRadar** is a machine learning project that predicts high-demand taxi pick-up locations in real-time, using a combination of historical data, real-time weather, and traffic information. The project is designed to assist taxi drivers in optimizing their routes and increasing their pick-up efficiency by suggesting nearby locations with high demand.

## Project Overview

- **Model Used**: Random Forest Regression and LSTM models
- **Accuracy Achieved**: Over 90%
- **Key Features**:
  - Predicts taxi demand based on historical and real-time data
  - Visualizes the top locations with predicted high demand
  - Calculates distance from the current location to suggested high-demand locations

## Demo

![image](https://github.com/user-attachments/assets/a8b63376-d882-4073-b039-7a5fdeb6e0b7)
![image](https://github.com/user-attachments/assets/da3d994d-0ab5-4236-92f1-e206b1d67b49)
![image](https://github.com/user-attachments/assets/1a84559b-ca8e-4e10-ae0a-475a6a94a49e)


## Dataset

The dataset used for this project contains historical taxi demand data, including:
- Date and Time
- Pick-up Latitude and Longitude
- Weather and Traffic data

The dataset was preprocessed to create features such as:
- Month, Day, Hour, Minute, Day of Week
- 2-hour time intervals

## Project Files

- `TaxiRadar.ipynb`: The main Jupyter notebook containing the code for data preprocessing, model training, prediction, and visualization.
- `combinedTaxiDemandSingapore.csv`: The dataset used in the project (not included due to size).
- `taxi_demand_model.joblib`: The trained machine learning model (not included due to size; see below for download instructions).
