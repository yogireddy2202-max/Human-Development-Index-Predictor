# Human-Development-Index-Predictor
# Human Development Index Predictor

## Overview

The Human Development Index (HDI) Predictor is a Machine Learning-based web application that predicts a country's Human Development Index score using key socio-economic indicators. The application is built with Flask and provides an easy-to-use interface where users can enter input values and receive an HDI prediction along with the corresponding development category.

## Features

* Predicts HDI score using Machine Learning.
* User-friendly web interface developed with Flask.
* Uses health, education, and income indicators for prediction.
* Displays predicted HDI score and development category.

## Technologies Used

* Python
* Flask
* HTML
* CSS
* Scikit-learn
* Pandas
* NumPy
* Joblib

## Dataset

The dataset contains the following features:

* Life Expectancy
* Expected Schooling
* Mean Schooling
* GNI per Capita
* HDI (Target Variable)

## Machine Learning Model

The project evaluates multiple regression algorithms for HDI prediction. The trained model is saved and integrated into the Flask application to generate predictions.

## Project Structure

```text
HDI_Predictor/
├── app.py
├── data/
├── models/
├── notebooks/
├── static/
├── templates/
├── screenshots/
└── README.md
```

## How to Run the Project

1. Download or clone the repository.
2. Open the project folder.
3. Install the required Python libraries.
4. Run the application:

   ```
   python app.py
   ```
5. Open the local URL displayed in the terminal (for example, http://127.0.0.1:5000).

## Future Enhancements

* Improve prediction accuracy with additional data.
* Deploy the application on a cloud platform.
* Add interactive data visualizations.
* Enable batch predictions for multiple records.




