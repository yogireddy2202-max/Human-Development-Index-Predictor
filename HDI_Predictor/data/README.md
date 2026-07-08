# Human Development Index Predictor

## Project Overview

The Human Development Index (HDI) Predictor is a Machine Learning based web application that predicts a country's HDI score using health, education, and income indicators.

The model uses:
- Life Expectancy
- Expected Years of Schooling
- Mean Years of Schooling
- GNI per Capita

The predicted HDI score is classified into development levels:
- Low Human Development
- Medium Human Development
- High Human Development
- Very High Human Development


## Project Architecture

Dataset
↓
Data Preprocessing
↓
Exploratory Data Analysis
↓
Feature Engineering
↓
Machine Learning Model Training
↓
Model Deployment using Flask
↓
Web Application


## Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

### Deployment
- Flask
- HTML
- CSS


## Machine Learning Approach

### Problem Type:
Regression

### Target Variable:
HDI Score

### Features:
- Life Expectancy
- Expected Schooling
- Mean Schooling
- Log Transformed GNI
- Education Index


## Model Used

Random Forest Regression was used because it can capture complex relationships between development indicators and HDI scores.


## Application Features

- User-friendly web interface
- HDI prediction
- Development category classification
- Interactive Flask application


## Project Screenshot

(Add your screenshot here)

![HDI Predictor](screenshots/hdi_predictor.png)


## How to Run the Project

Install required libraries:

pip install -r requirements.txt


Run Flask application:

python app.py


Open browser:

http://127.0.0.1:5000/