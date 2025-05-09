# Python API Challenge

This repository showcases the use of Python, APIs, and data visualization techniques to collect, analyze, and present weather data across the globe. The project is organized into two main parts: **WeatherPy** and **VacationPy**.

## Table of Contents

- [Overview](#overview)
- [WeatherPy](#weatherpy)
- [VacationPy](#vacationpy)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Overview

The project demonstrates how to integrate multiple APIs, perform data analysis with Python, and visualize results using maps and charts. It includes:

- Retrieving weather data for random global cities using the OpenWeatherMap API
- Analyzing and visualizing weather trends
- Identifying ideal vacation spots based on specific weather conditions
- Mapping hotel locations using the Geoapify API

## WeatherPy

This notebook:

- Generates random geographic coordinates
- Identifies the nearest city using the `citipy` library
- Uses the OpenWeatherMap API to retrieve weather data for each city
- Analyzes the relationship between weather variables and latitude
- Visualizes data using scatter plots and linear regression (SciPy)

## VacationPy

This notebook:

- Filters WeatherPy data for cities with ideal vacation conditions (e.g., temp, humidity, cloudiness)
- Uses Geoapify to find nearby hotels
- Plots selected vacation destinations and hotel markers on an interactive map

## Technologies

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- SciPy
- Citipy
- OpenWeatherMap API
- Geoapify API
- HvPlot

## Installation

```bash
git clone https://github.com/msmith150/python-api-challenge.git
cd python-api-challenge
pip install -r requirements.txt
 
