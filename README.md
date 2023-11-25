# Epsilon_AI
Billionaires Statistics Dataset
## Introduction

This repository contains a Python script for analyzing a dataset of billionaires. The dataset includes information such as rank, net worth, category, age, country, and various economic indicators for each billionaire.


## Billionaire Dataset Fields

- **rank:** The ranking of the billionaire in terms of wealth.
- **finalWorth:** The final net worth of the billionaire in U.S. dollars.
- **category:** The category or industry in which the billionaire's business operates.
- **personName:** The full name of the billionaire.
- **age:** The age of the billionaire.
- **country:** The country in which the billionaire resides.
- **city:** The city in which the billionaire resides.
- **source:** The source of the billionaire's wealth.
- **industries:** The industries associated with the billionaire's business interests.
- **countryOfCitizenship:** The country of citizenship of the billionaire.
- **organization:** The name of the organization or company associated with the billionaire.
- **selfMade:** Indicates whether the billionaire is self-made (True/False).
- **status:** "D" represents self-made billionaires (Founders/Entrepreneurs) and "U" indicates inherited or unearned wealth.
- **gender:** The gender of the billionaire.
- **birthDate:** The birthdate of the billionaire.
- **lastName:** The last name of the billionaire.
- **firstName:** The first name of the billionaire.
- **title:** The title or honorific of the billionaire.
- **date:** The date of data collection.
- **state:** The state in which the billionaire resides.
- **residenceStateRegion:** The region or state of residence of the billionaire.
- **birthYear:** The birth year of the billionaire.
- **birthMonth:** The birth month of the billionaire.
- **birthDay:** The birth day of the billionaire.
- **cpi_country:** Consumer Price Index (CPI) for the billionaire's country.
- **cpi_change_country:** CPI change for the billionaire's country.
- **gdp_country:** Gross Domestic Product (GDP) for the billionaire's country.
- **gross_tertiary_education_enrollment:** Enrollment in tertiary education in the billionaire's country.
- **gross_primary_education_enrollment_country:** Enrollment in primary education in the billionaire's country.
- **life_expectancy_country:** Life expectancy in the billionaire's country.
- **tax_revenue_country_country:** Tax revenue in the billionaire's country.
- **total_tax_rate_country:** Total tax rate in the billionaire's country.
- **population_country:** Population of the billionaire's country.
- **latitude_country:** Latitude coordinate of the billionaire's country.
- **longitude_country:** Longitude coordinate of the billionaire's country.

- # Billionaires Dataset Analysis




## Libraries Used

- Pandas
- NumPy
- Plotly Express
- Datetime

## How to Use

1. Install the required libraries:

    ```bash
    pip install pandas numpy plotly datetime
    ```

2. Run the script:

    ```bash
    python billionaires_analysis.py
    ```

## Importing the Data

The script reads the data from a CSV file named "Billionaires Statistics Dataset.csv" using Pandas.

## Exploratory Data Analysis (EDA)

- The script checks for duplicated values and missing values in the dataset.
- It performs univariate and bivariate analyses using Plotly Express to visualize and understand the data.

## Data Cleaning

- Data types are adjusted (e.g., converting float columns to int).
- NaN values in certain columns are filled with appropriate values.
- Unnecessary columns are dropped.
- Outliers in certain columns are handled.

## Visualizations

- Various visualizations are created, including violin plots, box plots, histograms, and scatter plots, to explore the distribution and relationships within the data.

## Analysis

The script answers several questions about the dataset, such as identifying the youngest billionaire, analyzing the distribution of genders, exploring the relationship between education and wealth, and more.

## Results

The results of the analysis are presented in both visualizations and textual answers to specific questions.

## Conclusion

This script provides a comprehensive analysis of the given billionaires dataset, offering insights into the demographics, industries, and economic indicators associated with the world's billionaires.

Feel free to modify the script or adapt it to your specific needs.

