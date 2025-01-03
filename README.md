# ML for Weather Forecast: Predicting FWI

This project focuses on using machine learning techniques to predict the Fire Weather Index (FWI) from weather data. The FWI is a numerical rating of fire intensity, which is crucial for forest fire management.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The goal of this project is to develop a machine learning model that can accurately predict the Fire Weather Index (FWI) based on various weather parameters. This can help in early detection and management of forest fires.

## Dataset
The dataset used in this project contains historical weather data and corresponding FWI values. The key features include:
- Temperature
- Relative Humidity
- Wind Speed
- Rainfall
- Fine Fuel Moisture Code (FFMC)
- Duff Moisture Code (DMC)
- Initial Spread Index (ISI)
- Classes (Fire/Not Fire)
- Region

The dataset includes 244 instances from two regions in Algeria, covering the period from June 2012 to September 2012.

## Installation
To run this project, you need to have Python and the following libraries installed:
- pandas
- numpy
- scikit-learn
- flask
- matplotlib

You can install the required libraries using:
```bash
pip install -r requirements.txt
```

## Usage
1.Clone the Repository:
```
git clone https://github.com/yourusername/ml-weather-forecast.git
```
2.Navigate to the project directory
```
cd ml-weather-forecast
```
3.Run the Flask application:
```
python application.py
```
## Model Training
The machine learning model used in this project is a Ridge Regression model. The model is trained on historical weather data to predict the FWI. The training process includes data cleaning, feature selection, and scaling.

## Results
The model's performance is evaluated using metrics such as Mean Absolute Error (MAE) and R-squared (R²). The results indicate that the model can effectively predict the FWI with reasonable accuracy.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.