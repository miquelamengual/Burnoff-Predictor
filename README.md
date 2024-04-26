# Burnoff-Predictor
This GitHub repository hosts the code and related resources for Miquel Amengual Verdera's Capstone Project at IE University: "Advancing Aircraft Fuel Efficiency Forecasting: The Impact of Weather-Integrated Machine Learning Models on Fuel Consumption Predictions" 

## Project Overview & Objectives
This research aims to understand how the integration of weather data into machine learning models can improve the accuracy of fuel consumption predictions for commercial flights. Thus, the main objective of this project is to develop a machine learning model that combines weather data with flight attributes to forecast fuel consumption more accurately than existing models. Furthermore, we aim to gain an understanding of the main drivers of fuel predictions, as well as potential considerations involved in integrating these machine learning models into existing airline systems.

## Repository Structure
- **EDA**: This Jupyter Notebook contains the exploratory data analysis (EDA) for the Ryanair dataset used in the project. It includes visualizations and statistical summaries to understand the distributions, correlations, and patterns in the data.
- **data_preprocessing.ipynb**: This document provides the procedures for cleaning and preparing the Ryanair data for analysis, and feature engineering to create the FuelWeight, AircraftAge, and Distance variables. 
- **weather_preprocessing.ipynb**: This notebook details the process of extracting and preprocessing weather data from the ERA5 climate database. It outlines the steps taken to integrate weather variables (pressure, temperature, humidity, wind, and precipitation).
- **baseline_model_linear_models.ipynb**: In this notebook, baseline linear models are developed and tested on the Ryanair data with and without feature engineering. The performance of these models is evaluated to establish a benchmark for comparison with more complex models and the integration of weather data.
- **baseline_model_ensemble_models.ipynb**: This notebook focuses on constructing and evaluating baseline ensemble machine learning models using Ryanair data with and without feature engineering.
- **weather_model_linear_models.ipynb**: This notebook explores the impact of integrating weather data from the ERAS 5 climate database into linear models with Ryanair flight data. 
- **weather_model_ensemble_models.ipynb**: This notebook explores the impact of integrating weather data from the ERAS 5 climate database into ensemble models with Ryanair flight data. 


