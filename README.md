# NYC-Cab-Services-Analysis

## Overview
This project analyzes the shifting preferences for cab services over public transportation in New York City, exploring socio-economic factors, urban demographics, and other influences on commuter decisions.

## Objective
The main goal is to understand what drives the increasing preference for cabs in NYC and to develop a predictive model that helps cab drivers make more profitable decisions.

## Datasets
Description of all datasets used in the project:
- **NYC TLC Trip Records**: Detailed data on taxi trips including times, locations, distances, fares, etc.
- **NYC Taxi Zone Dataset**: Geometric and location data for taxi operational zones.
- **NYC Weather Data**: Comprehensive weather patterns recorded in Central Park.
- **NYPD Crime Statistics**: Crime data across NYC transit districts.

## Methodology
- **Data Preprocessing**: Techniques and processes used to prepare the data.
- **Analysis**: Approaches taken to analyze the data, including comparative analysis and impact studies.
- **Modeling**: Details about the neural network model developed to predict taxi fares.
- 
### Download Datasets
Due to the large size of the data files, they are not included in the repository. Please follow the links below to download the required datasets:
- **TLC Trip Record Data**: Download from [NYC.gov TLC Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page).
- **For-Hire Vehicle Data**: Download from [NYC.gov FHV Data](https://www.nyc.gov/site/tlc/about/fhv-trip-record-data.page).
- **Taxi Zones GeoJSON**: Directly included in the repository under the file name `NYC Taxi Zones.geojson`.
- **Weather Data**: Provided in the repository as `NYC Weather.csv`.
- **Crime Data**: Utilize Excel files such as `Penalcode.xlsx` and `Transit district crimes.xlsx` already included in the repository.

### Project Files Structure
This section details the files included in this repository and their purpose:
- **`Analysis_Implementation.ipynb`**: Main analysis notebook containing the full workflow of data analysis and modeling.
- **`Copy of datapreping (1).ipynb`**: Notebook for preprocessing and preparing the data for analysis.
- **`NYC Taxi Zones.geojson`**: GeoJSON file containing the geographic boundaries of taxi zones in NYC.
- **`NYC Weather.csv`**: CSV file containing weather data for NYC, utilized in the analysis.
- **Excel files**:
  - **`Penalcode.xlsx`**: Contains crime codes and their descriptions.
  - **`Transit district crimes.xlsx`**: Provides crime statistics across various transit districts.

## Key Findings
Summarize the main insights from the project, highlighting how these can aid taxi drivers.

- **Python**: Core programming language for data analysis and model development.
- **Pandas**: For data manipulation and analysis 
- **NumPy**: For numerical computing and array operations 
- **GeoPandas**: Extends Pandas for geospatial data analysis 
- **Matplotlib**: For creating static, animated, and interactive visualizations in Python 
- **Seaborn**: For statistical data visualization built on Matplotlib 
- **Contextily**: Adds basemap tiles to geospatial plots
- **Openpyxl**: To work with Excel files 
- **OS**: Used for file path management and interacting with the system.
- **Warnings**: To handle warning messages and manage clean execution.
- **Shape**: For handling shape files and geospatial data.


## References
A detailed list of all data sources and research articles referenced in the project.
