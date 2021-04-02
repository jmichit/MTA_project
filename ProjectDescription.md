# Using.MTA Turnstile data to find highest foot traffic subway stations in Queens
John Michitsch

## Abstract
This project is a Exploratory Data Analysis exercise to use Python (specifically the Matplotlib and Pandas packages) and SQL (utilizing a SQLite3 database) to analys a real world data set = NYC Metropolitan Transit Authority turnstile data - entries and exits at each of its subway stations throughout the 5 boroughs (all 5 boroughs - Manhattan, Queens, Brooklyn, The Bronx, and Staten Island (yes, Staten Island even has a subway!) 


## Design
Innovative marketing firm wants to find high foot traffic areas in NYC to market new beverage products. Company flexible on locations, time of day, week day, weekend, or holiday. Upon further reflection, company decides to eschew the obviously high volume of Manhattan stops to focus on an outer borough - Queens - to find more subtle options than the well known high trafficed commuter hubs of Penn Station or Grand Central in Mahattan. Benefit might be to capture more local traffic that out-of-town commuters. 
Analysis starts with EDA tasks of understanding the data using statistics and graphics and performance of needed data cleaning using pandas.

### Levels of analysis
1 Big picture overall average traffic by station
2 Time series of traffic over observation period 
3 View of traffic by day of week seeing if there is any variability by season

## Data

### Data Sources
* The primary data source is comma separated values (CSV) formatted files containing weekly turnstile data. Each row represents the value of the entry and exit counters for a specific turnstile for a specific date and time, usually taken in 4 hour intervals. 
* A supplemental data source employed, also available via the same MTA website is a list of stations and station related data such as subway lines, borough, structure (subway, elevated, etc.), longitude and latitude, etc. 
### Data Pipeline
* Python script used to systematically import data files for the period from August 2020 to March 2021 to provide a good sample of activity at each station 
* Command line tools used to merge data
* Data loaded to SQLite3 data base
* Station data manually downloaded and imported to SQLite3 database.

## Algorithms
* Basic EDA 

## Tools
- SQLite3 used to house the combined data 
- Numpy and Pandas for data manipulation
- Matplotlib for plotting

## Communication
Findings are consolidated in a pdf presentation and the supporting Jupyter Notebooks can also be found here. 









