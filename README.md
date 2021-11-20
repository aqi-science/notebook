# EDS220 Fall2021 Final Project and HW3

## Analyzing Air Quality Trends in the US with EPA AQI Data

#### Student Authors: Grace Lewin, Felicia Cruz, & Steven Cognac

#### Due: November 19, 2021

## Motivation and Project Goal
This final assignment is a student led, data intensive analysis on a dataset our choosing.  Air quality serves as an important indicator of human health and the environment. Under the Clean Air Act, U.S. the Environmental Protection Agency (EPA) established National Ambient Air Quality Standards (NAAQS) for six common air pollutants: ozone, particulate matter (PM2.5 and PM10), sulfur dioxide, carbon monoxide, and nitrogen dioxide. Combined, these pollutants form the U.S. Air Quality Index (AQI) for reporting air quality.  Additional data on NAAQS and source data can be found at here at:
- https://www.epa.gov/criteria-air-pollutants/naaqs-table
- https://aqs.epa.gov/aqsweb/airdata/download_files.html#AQI

The purpose of this project is to assess how air quality in the United States has changed over time from 1980 to 2020. We will use daily Air Quality Index (AQI) data by US county and metropolitan areas for our analysis. This data is made available by the US EPA and is freely accessible. 

## Intended Purpose and Important Concepts
This project is intended for educational purposes. Student authors practiced the following skills and commands:
- dataset searching
- html parsing
- index joins
- data subsetting
- setting coordinate reference systems
- calculating rolling means
- time series plotting


## Setup
The following **packages** were utilized during this analysis:

Data Analysis
- pandas
- numpy
- matplotlib
- geopandas
- shapely
- contextily

Data Download
- datetime
- bs4
- zipfile
- io
- urllib
- requests

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aqi-science/notebook/main)
