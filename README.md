# Earthquake-Prediction-ML
Machine Learning Based Earthquake Risk Classification and Magnitude Prediction using Real USGS Data.


# Earthquake Prediction using Machine Learning

## Overview

This project builds a Machine Learning based earthquake prediction system using **real seismic data** collected from the USGS Earthquake Catalog.

The system performs:

• Earthquake Risk Classification  
• Magnitude Prediction  
• Real-time Prediction System

Dataset Source:

USGS Earthquake Catalog API

2000 - 2024

South Asia Region

Magnitude ≥ 2.5

---

## Features

✔ Real Data Collection (No Synthetic Data)

✔ Automatic Data Cleaning

✔ Exploratory Data Analysis

✔ Machine Learning Pipelines

✔ Cross Validation

✔ Hyperparameter Tuning

✔ Real-time Prediction System

✔ Model Saving and Loading


---

## Machine Learning Models

### Classification Models

• Logistic Regression

• Random Forest Classifier


### Regression Models

• Linear Regression

• Random Forest Regressor


---

## Machine Learning Pipelines

Pipeline 1

Logistic Regression + RF Regressor


Pipeline 2 (Champion Model)

Random Forest Classifier + Linear Regression


Pipeline 3

Logistic Regression + Linear Regression


Pipeline 4

Random Forest Classifier + RF Regressor


---

## Dataset

Data Source:

USGS Earthquake API


Features Used:

Latitude

Longitude

Depth

Year

Month


Target Variables:

is_earthquake

Magnitude


Threshold:

Magnitude ≥ 4.5 → Earthquake

Magnitude < 4.5 → Minor


---

## Model Performance

Metrics Used:

Accuracy

Precision

Recall

F1 Score

MAE

RMSE

Cross Validation Used:

5-Fold Cross Validation


---

## Real-time Prediction System

Example:

