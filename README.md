# Climate Change Data Analysis


## Overview
This jupyter notebook takes in a csv file and performs multiple different data analyses on the data to help show the changes happening within our planet.

## Features
- **Temperature graphs**: provides a graph of a selected country that illustrates the changes in the annual mean in temperature over the years
- **Statistics**: performs statistical analysis on the data and prints the statistics from the data
- **Geodata Map**: creates colored maps of the data showing the difference in temperature and the change in temperature each country has gone through
- **Comparison**: allows the user to provide a set of data to compare to the original data to find the correlation between the two
- **T-test**: performs a T-test on the data and prints the T-statistic and the P-value

## Technologies Used
### Front-end
- Jupyter Notebooks
### Backend
- Python for the backend logic

## Libraries
- pandas to read the csv file
- matplotlib to create the graphs
- seaborn to create the lineplots
- geopandas for creating the world map using a geojson
- scipy for the T-test analysis
- statsmodels for the statistical analysis
- os to ensure that the inputted csv file from the user exists
