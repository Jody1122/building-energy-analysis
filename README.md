# Building Energy Analysis - The City of Calgary

## Introduction

Rising energy consumption and greenhouse gas emissions pose a significant threat to the environment and public health. This project analyzed building energy consumption and greenhouse gas (GHG) emissions in the city of Calgary by integrating multiple datasets. I utilized four primary datasets from the City of Calgary Open data portal described as follows; Civic Census Data, Building Energy Benchmarking Data, Corporate Energy Consumption Data and Community-wide GHG Inventory Data.

## Objectives

The project objective is to analyze data on energy consumption and GHG emissions from residential, commercial, and industrial buildings in Calgary. This project is essential for developing strategies to reduce carbon footprints, improve energy efficiency, and contribute to the city's environmental sustainability efforts.


## Methods

Firstly, I used Python to perform data cleaning and wrangling to ensure the dataset is fit for analysis, dealing with missing values, outliers and handling irrelevant columns. Next, I uploaded cleaned datasets to SQL database and used SQL queries to retrieve data according to my guiding questions. Finally, I used Python MathplotLib for data visualization.

My Guiding Questions are as followings:

Electricity Consumption
* What is the consumption trend of Electricity and Solar Power by corporate organization on monthly and yearly basis from 2014-2023?
* Which energy description is majorly used across different business units by year and by month

Demographic Dataset
* How has resident count varied over the years in the City of Calgary? Can this be correlated with building energy consumption? Which dwelling type is predominant in the City of Calgary?
* How does population distribution across Calgary communities correlate with building energy consumption?

Gas Emission Dataset
* How have the GHG emissions trends changed over the year? In what year is the GHG the highest/lowest?
* Which sectors contribute the most to GHG emissions? What kind of emission source contributes the most in each sector by percentage?

Building Energy Benchmark Dataset
* What is the total building energy consumption and emissions over time? What is the total emissions by property type?
* What is the trend of energy consumption and coresponding emissions for buildings?

## Tech stacks
* Python
* MySQL


## License

This project is licensed under the MIT License.

## References

1. Building Energy and Emissions Performance by Property Type - BenchmarkYYC | Open Calgary (November 13, 2023). Available at: https://data.calgary.ca/Environment/Building-Energy-and-Emissions-Performance-by-Prope/yrvn-w2q3/about_data (Accessed: 5 March 2024).

2. Building Energy Benchmarking - City of Calgary | Open Calgary (25 September 2023). Available at: https://data.calgary.ca/Environment/Building-Energy-Benchmarking-City-of-Calgary/8twd-upbv/about_data (Accessed: 5 March 2024).

3. Civic Census by Community and Dwelling Structure | 	Open Calgary (3 September 2019). Available at: https://data.calgary.ca/Demographics/Civic-Census-by-Community-and-Dwelling-Structure/set9-futw (Accessed: 5 March 2024).

4. Community-wide Greenhouse Gas (Ghg) Inventory | Open Calgary (1 November 2023). Available at: https://data.calgary.ca/Environment/Community-wide-Greenhouse-Gas-GHG-Inventory/m7gu-3xk5/about_data (Accessed: 1 March 2024).

5. Corporate Energy Consumption | Open Calgary (1 March 2024). Available at: https://data.calgary.ca/Environment/Corporate-Energy-Consumption/crbp-innf/about_data (Accessed: 2 March 2024).

6. Management, E. & S. (no date a) BenchmarkYYC, https://www.calgary.ca. Available at: https://www.calgary.ca/content/www/en/home/environment/climate/building-energy-benchmarking-program.html (Accessed: 5 March 2024).

