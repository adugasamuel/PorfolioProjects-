
# COVID-19 Data Analysis Project

## Overview

This project involves a comprehensive analysis of COVID-19 data using SQL. The data source was obtained from [Our World in Data](https://ourworldindata.org/covid-deaths). The dataset consists of global COVID-19 cases, including the number of infected persons, total deaths, vaccinations, and many other related metrics. The analysis covers all cases from March 2020 to July 2024.

## Data Source

The data for this project was obtained from [Our World in Data](https://ourworldindata.org/covid-deaths) which was splited into two main datasets for easy analysis:
- **CovidDeaths**: Contains data on COVID-19 global cases of infected persons and total deaths.
- **CovidVaccinations**: Contains data on COVID-19 vaccinations.

## Objectives

The main objective of this project was to carry out an exploratory analysis using SQL to gain insights into the COVID-19 pandemic. The key questions explored in this analysis include:
1. What is the percentage of the total cases recorded compared to the total deaths recorded?
2. What is the percentage of total cases recorded vs total population by countries?
3. Which country has the highest infection rate?
4. Which countries recorded the highest number of death cases per population?
5. What is the global death rate percentage for COVID-19?
6. What is the total population of vaccination received per country?
7. What is the mortality rate?
8. Which age group has the highest infection rate?

## SQL Analysis

SQL was used to perform the exploratory data analysis. Various queries were written to extract, transform, and analyze the data to answer the questions listed above. Views were created to facilitate data visualization and further analysis.

## Key Insights

Some of the key insights gained from this analysis include:

- **Total Cases and Deaths**:
  - Globally, the total number of cases recorded is 775,741,465.
  - The total number of deaths globally is 7,057,367, resulting in a global death rate of approximately 1%.

- **Country-Specific Insights**:
  - The United States recorded the highest death rate per population, with 103,436,829 infected persons and 1,190,579 deaths.
  - The top five countries with the highest infection rates are the United States, Brazil, India, Russia, and Mexico.
  - North America recorded the highest number of death cases among continents, followed by South America and Asia. North America alone recorded a total of 1,190,579 deaths, while Oceania had the least number of deaths with 25,236.

- **Vaccination Insights**:
  - The analysis included data on the total population of vaccinated individuals per country.

## Data Visualization

Views were created using SQL to facilitate data visualization. These views can be used in tools like Tableau or Power BI to create interactive dashboards and visual representations of the data.


## Conclusion

This project demonstrates the use of SQL for analyzing a large dataset related to the COVID-19 pandemic. The insights provide valuable information on the trends and impacts of COVID-19 over the years. The views created facilitate further exploration and visualization of the data.

## Acknowledgements

Special thanks to [Our World in Data](https://ourworldindata.org/) for providing the dataset used in this analysis.

