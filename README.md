# Weather Data Analysis Project

This project analyzes a dataset of weather conditions recorded throughout 2012. The data includes various meteorological measurements taken at hourly intervals.

## Dataset Overview

The dataset (`weatherdata.csv`) contains the following columns:
- Date/Time
- Temperature (°C)
- Dew Point Temperature (°C)
- Relative Humidity (%)
- Wind Speed (km/h)
- Visibility (km)
- Pressure (kPa)
- Weather Condition

## Analysis Highlights

The project includes various data exploration and analysis tasks:

1. Basic data inspection (shape, columns, data types)
2. Unique weather conditions and their frequency
3. Statistical analysis (mean, standard deviation, variance) of different weather parameters
4. Filtering data based on specific conditions (e.g., snow events, high wind speed with specific visibility)
5. Grouping and aggregating data by weather conditions

## Key Findings

- The dataset contains 8,784 hourly records (full year of data)
- There are 50 unique weather conditions recorded
- Temperature ranges from -21.3°C to 32.6°C
- Wind speed ranges from 0 to 83 km/h
- Visibility ranges from 0.2 km to maximum recorded value (likely clear conditions)

## Tools Used

- Python
- Pandas for data manipulation and analysis

## Getting Started

1. Ensure you have Python and Pandas installed
2. Clone this repository
3. Place the `weatherdata.csv` file in the project directory
4. Run the analysis scripts to reproduce the results

## Future Work

- Visualize the data using matplotlib or seaborn
- Perform time series analysis to identify weather patterns
- Build predictive models for weather conditions

Feel free to contribute to this project by opening issues or submitting pull requests!
