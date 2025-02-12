# Soft Sensor Development Using Machine Learning

## 📋 Introduction

This repository reflects my interest in exploring machine learning techniques that merge the capabilities of artificial intelligence with chemical engineering. Soft sensors are valuable tools used to model process variables that cannot be measured directly with physical sensors. They provide real-time estimations based on other available data, enhancing process monitoring and control. In this project, the focus is on predicting the concentration of a chemical component—a variable that often lacks direct measurement capabilities in industrial environments.

## 🚀 Project Overview

The notebook includes the development of a soft sensor using three machine learning models:

- **Linear Regression**
- **Random Forest Regressor**
- **Support Vector Regressor (SVR)**

The models are trained on simulated process data, including flow rate, temperature, and pressure, to predict the concentration of a chemical component.

## 📊 Dataset

Synthetic data was generated to simulate industrial conditions:

- **Flow Rate** (L/min)  
- **Temperature** (°C)  
- **Pressure** (bar)  
- **Concentration** (target variable)  

## ⚙️ Model Evaluation

The models were evaluated based on the following metrics:

- **Mean Squared Error (MSE):** Measures the average squared difference between actual and predicted values.
- **R-squared (R²):** Indicates the proportion of variance explained by the model. 

## 📦 Repository Structure

- `soft_sensor_notebook.ipynb`: Main notebook containing data simulation, model training, evaluation, and visualization.  
- `README.md`: Project documentation.  


*This project highlights my passion for merging AI with chemical engineering to drive innovative solutions in industrial process monitoring.*
