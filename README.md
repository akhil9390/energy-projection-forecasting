# Energy Demand Forecasting Using Time Series Deep Learning

This project focuses on forecasting energy production volumes using historical oil and gas data. The workflow includes data loading, preprocessing, exploration, model development, evaluation and future forecasting. Deep learning models are used to capture temporal patterns and support long term energy trend prediction.

## Dataset

Source  
US Oil and Gas Production and Disposition dataset from 2015 to 2025.

Link  
https://www.kaggle.com/datasets/pinuto/us-oil-and-gas-production-and-disposition-20152025

## Project Objectives

Understand production trends in the oil and gas industry.  
Prepare and clean the dataset for time series forecasting.  
Explore the data distribution, volume trends and missing values.  
Build and train LSTM based deep learning models for forecasting.  
Generate predictions for both historical test portions and future timestamps.

## Project Structure

Data Loading  
The dataset is loaded using Pandas and inspected for structure, column types and unique disposition classes.

Data Preparation  
Date columns are converted to datetime.  
Data is grouped and aggregated by year and month.  
Missing values are handled.  
Features and labels are scaled.  
Sequences are generated for time series forecasting.

Exploratory Data Analysis  
Visualizations show production volume patterns across months and years.  
Distribution and trend plots help understand seasonality and long term behavior.

Model Development  
LSTM layers are used to capture time dependent patterns.  
The model is trained on historical sequences.  
Training performance metrics are monitored.

Evaluation  
Predictions are compared with actual values on the test dataset.  
Trend plots visualize model behaviour on unseen data.

Future Forecasting  
The project generates predictions for future time periods beyond the available dataset and outputs structured forecast tables.

## Requirements

Python  
Pandas  
NumPy  
Matplotlib  
Scikit Learn  
TensorFlow

## How to Run

Place the dataset in the working directory or update the file path in the notebook.  
Run all cells in the notebook sequentially.  
The notebook will generate plots, training outputs and forecasting tables.

## Output

Cleaned and preprocessed dataset ready for modelling.  
Exploratory plots highlighting trends.  
Trained LSTM forecasting model.  
Predicted production values for testing windows.  
Future forecast results printed as tables.

## Notes

The model can be improved by tuning hyperparameters or experimenting with additional architectures such as GRU or hybrid models.