# PM2.5 Air Pollution Prediction using Machine Learning

This project investigates the use of machine learning techniques to predict PM2.5 air pollution levels using measurements from other air pollutants.

The project was developed as part of the **DIL700 Artificial Intelligence course at University West**.

## Project Objective

Air pollution is a major environmental and public health issue. Fine particulate matter (PM2.5) is especially harmful because it can penetrate deep into the lungs and bloodstream.

The objective of this project is to build machine learning models capable of predicting PM2.5 concentrations using other environmental pollutant measurements.

## Dataset

The dataset contains air pollution measurements collected in **Seoul**.  
Each record includes the following variables:

- SO2 – Sulfur dioxide concentration
- NO2 – Nitrogen dioxide concentration
- O3 – Ozone concentration
- CO – Carbon monoxide concentration
- PM10 – Particulate matter (10 µm)
- PM2.5 – Fine particulate matter (target variable)

Additional features extracted from timestamps:

- Hour of the day
- Month

The dataset contains **over 600,000 samples**.

## Machine Learning Models

The following algorithms were implemented and evaluated:

- Linear Regression
- Random Forest
- Artificial Neural Network
- Improved Neural Network

## Evaluation Metrics

The models were evaluated using standard regression metrics:

- RMSE – Root Mean Squared Error
- MAE – Mean Absolute Error
- R² – Coefficient of Determination

## Results

The **Improved Neural Network** achieved the best performance.

| Model | RMSE | MAE | R² |
|------|------|------|------|
| Linear Regression | 42.14 | 12.19 | 0.078 |
| Random Forest | 42.17 | 9.22 | -0.004 |
| Neural Network | 38.01 | 7.49 | 0.184 |
| Improved Neural Network | **37.89** | **7.20** | **0.189** |

## Project Structure
