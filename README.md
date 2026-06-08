# Cost of Living for Young Immigrants in Israel

## Project Overview

This project analyzes the cost of living for young immigrants in Israel by comparing four major cities:

* Tel Aviv
* Ramat Gan
* Haifa
* Jerusalem

The analysis combines rental market data with salary, transportation, grocery basket, and municipal tax (Arnona) data to evaluate affordability across cities.

## Objectives

* Compare rental prices across cities
* Estimate monthly living costs
* Calculate affordability metrics
* Identify which cities are more accessible for young immigrants

## Data Sources

* Madlan (rental listings)
* National Insurance Institute (Bituach Leumi)
* Rav-Kav Online
* Numbeo
* Municipal Arnona ordinances

## Tools Used

* Python
* Pandas
* NumPy
* Tableau
* Google Colab

## Methodology

### Salary Data

Gross monthly salaries were used because publicly available salary statistics are reported in gross terms, allowing a consistent comparison across cities.

### Rental Data

Median rent was used instead of average rent to reduce the impact of luxury properties and extreme outliers, particularly in Jerusalem.

### Outlier Filtering

Listings with unrealistic price-per-square-meter values were removed before analysis.

### Arnona Calculation

Arnona costs were estimated using municipal tax rates and a standardized apartment size across all cities to ensure comparability.

## Key Metric

### Rent-to-Salary Ratio (%)

This metric measures the percentage of average gross salary required to pay monthly rent in each city.

## Dashboard Metrics

The Tableau dashboard compares cities using:

* Average Salary
* Median Rent
* Total Monthly Cost
* Disposable Income
* Rent-to-Salary Ratio

## Key Findings

* Tel Aviv offers the highest salaries but also the highest housing costs.
* Jerusalem shows the highest rent burden relative to income.
* Haifa provides the lowest rental costs among the analyzed cities.
* Ramat Gan offers a strong balance between income and living expenses.

## Author

Juan Epstein  
Developers Institute – Data Analysis Bootcamp
