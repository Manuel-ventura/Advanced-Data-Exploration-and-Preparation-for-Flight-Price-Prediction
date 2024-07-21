# Advanced Data Exploration and Preparation for Flight Price Prediction

## Project Overview
This project focuses on the detailed exploratory data analysis (EDA), cleaning, visualization, and pre-processing of flight price data. The aim is to prepare a robust dataset that can be used to build predictive models for flight prices. By understanding and refining the data, we enhance the accuracy and effectiveness of subsequent analyses and predictions.

## Table of Contents
- [Installation](#installation)
- [Data Description](#data-description)
- [Usage](#usage)
- [Methodology](#methodology)
- [Visualization Insights](#visualization-insights)
- [Contributing](#contributing)
- [License](#license)

## Installation
To run this project, you will need Python and the following Python libraries installed:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

You can install these packages using pip:
```bash
pip install pandas numpy matplotlib seaborn notebook
```

## Data Description
The dataset contains detailed information on flight prices, destinations, sources, and various attributes related to flight timings and passenger preferences. Key columns include:
- `Price`: Ticket price for the flight.
- `Destination`: Destination airport of the flight.
- `Source`: Source airport of the flight.
- `Date_of_Journey`, `Dep_Time`, `Arrival_Time`: Schedule of the flights.
- `Duration`: Total duration of the flight.
- `Additional_Info`: Contains additional information about the flight.

## Usage
To run this project, clone the repository and execute the Jupyter notebook:
```bash
git clone https://github.com/Manuel-ventura/Advanced-Data-Exploration-and-Preparation-for-Flight-Price-Prediction.git
cd Advanced-Data-Exploration-and-Preparation-for-Flight-Price-Prediction
jupyter notebook
```

## Methodology
The project follows these steps:
1. **Data Loading**: Importing the data from CSV files.
2. **Exploratory Data Analysis (EDA)**: Analyzing the dataset to summarize its main characteristics.
3. **Data Cleaning**: Handling missing data, removing duplicates, and correcting errors to enhance data quality.
4. **Visualization**: Employing plots such as histograms, box plots, and violin plots to understand distributions and identify outliers.
5. **Pre-Processing**: Transforming data into a format suitable for modeling, which includes feature engineering and normalization.

## Visualization Insights
- Detailed analysis using violin plots to compare the distribution of prices across different destinations and sources.
- Identification of outliers and data skewness which are critical for predictive modeling accuracy.

## Contributing
Contributions to this project are welcome. Please ensure to update tests as appropriate.

## License
Distributed under the MIT License. See `LICENSE` for more information.
