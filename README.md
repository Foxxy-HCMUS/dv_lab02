# LAB 02 DATA VISUALIZATION: Time Series Analysis of Baltimore Crime Data

This project performs time series analysis on the Baltimore crime data repository to uncover trends and patterns.

## Data
Data world link: [https://data.world/data-society/city-of-baltimore-crime-data](https://data.world/data-society/city-of-baltimore-crime-data)

This dataset contains information about crimes reported in the city of Baltimore, Maryland, USA from 2012 to the end of 2016. It includes information about the time, location, type of crime, weapons used, etc.

Data files used:

- `crime.csv`

## Analysis

The following analyses were performed on the crime data:

- Visualization of crime frequency over time
- Analysis of seasonal and time-based patterns
- Crime hotspot analysis and mapping
- Comparing crime types and weapon usage
- Autocorrelation analysis to identify cyclical patterns
- Forecasting of future crime numbers using ARIMA and SARIMA models, finding best hyperparameters using auto-arima.

## Results

Key insights from the analysis include:

- Crime follows seasonal patterns, highest in summer months
- Assault increases on weekends, thefts more common on weekdays
- Crime hotspots concentrated in the downtown and eastern areas
- Handguns most commonly used weapon across all crime types

## Usage

1. Clone this repository
2. Create a Conda environment using
'''bash
conda env create -f <this file>
'''
3. Run the Jupyter notebook `timeseries.ipynb`.

Let me know if you have any questions about this repository!
