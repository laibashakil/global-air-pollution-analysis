# Global Air Pollution Analysis

## Introduction

This repository contains an in-depth analysis of global air pollution based on the **Global Air Pollution Dataset** sourced from Kaggle. The dataset provides valuable insights into air quality metrics across various countries and cities, including key indicators such as Air Quality Index (AQI), pollutant concentrations, and AQI categories. This README file serves as a guide to understanding the project, its objectives, findings, and how to reproduce the analysis.

## Dataset Information

-   **Dataset Source**: Kaggle
-   **Dataset Link**: [Global Air Pollution Dataset](https://www.kaggle.com/datasets/hasibalmuzdadid/global-air-pollution-dataset)

The dataset comprises the following variables:

-   `Country`: Name of the country
-   `City`: Name of the city
-   `AQI Value`: Overall AQI value of the city
-   `AQI Category`: Overall AQI category of the city
-   `CO AQI Value`: AQI value of Carbon Monoxide of the city
-   `CO AQI Category`: AQI category of Carbon Monoxide of the city
-   `Ozone AQI Value`: AQI value of Ozone of the city
-   `Ozone AQI Category`: AQI category of Ozone of the city
-   `NO2 AQI Value`: AQI value of Nitrogen Dioxide of the city
-   `NO2 AQI Category`: AQI category of Nitrogen Dioxide of the city
-   `PM2.5 AQI Value`: AQI value of Particulate Matter with a diameter of 2.5 micrometers or less of the city
-   `PM2.5 AQI Category`: AQI category of Particulate Matter with a diameter of 2.5 micrometers or less of the city

## Project Structure

The project is organized as follows:

-   **Data Acquisition**: The dataset is downloaded from Kaggle using the [OpenDatasets](https://github.com/JovianML/opendatasets) library and loaded into a Pandas DataFrame.
    
-   **Data Preparation and Cleaning**: This section includes data cleaning steps such as handling missing values and removing duplicates.
    
-   **Exploratory Analysis and Visualization**: In this section, various visualizations and analyses are performed to gain insights into global air pollution. Key visualizations include histograms, bar charts, correlation heatmaps, and pairplots.
    
-   **Findings**: The project presents important findings, including the top polluted countries, cities, and the impact of different pollutants on the Air Quality Index (AQI).
    
-   **Conclusion**: A summary of the key insights and implications of the analysis on air quality and pollution control.
    

## Reproducing the Analysis

To reproduce the analysis on your local machine, follow these steps:

1.  Clone this GitHub repository to your local machine.
    
2.  Ensure you have the necessary Python libraries installed.
    
3.  Download the dataset from the Kaggle link provided and place it in the project directory.
    
4.  Run the Jupyter Notebook `Global_Air_Pollution_Analysis.ipynb` to execute the analysis step by step.
    

## Contribute

If you wish to contribute to this project or report issues, please create a pull request or open an issue on the GitHub repository.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/laibashakil/global-air-pollution-analysis/blob/main/LICENSE) file for details.

## Acknowledgments

-   The dataset used in this analysis is sourced from Kaggle, and credit goes to the original data provider.

Thank you for exploring the Global Air Pollution Analysis project. Your contributions and feedback are welcome to improve the analysis and its insights.
