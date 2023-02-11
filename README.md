# COVID-19 Mobility Analysis
## Project Overview
This project explores the relationship between the number of daily positive cases of COVID-19 and several types of mobility levels in Jakarta. Correlation analysis is used to determine the correlation between these two variables. The results of this analysis provide insights into the impact of mobility on the spread of COVID-19 in Jakarta, and may inform public health policies aimed at controlling the spread of the virus. This project provides a valuable contribution to the understanding of the interplay between mobility and the spread of COVID-19, and can inform decision making to mitigate its impact

## Datasets
Two datasets were used for analysis.

The [first dataset](https://tiny.cc/Datacovidjakarta) provides data on the fatalities from COVID-19 in Jakarta.

The [second dataset](https://www.google.com/covid19/mobility/) provides data on the Community Mobility Report. This report maps movement trends over time by geography, across different categories of places such as retail and recreation, grocery stores and pharmacies, parks, public transport hubs, workplaces, and residential areas. The dataset was provided by Google.

## Data wrangling steps prior to analysis:
- Renaming column headers
- Dropping unnecessary columns
- Dropping duplicate rows/missing values
- Detecting outliers
- Merging data sets
- Sorting the data set per month

## Summary of Findings
- Initial analysis indicates the relationship between number of daily positive cases of Covid-19 and the mobility variables are not linear. The relationship between the response variable and the independent variable has a negative correlation, therefore it can be said that when the number of daily positive cases of Covid-19 has decreased, the mobility of the Indonesian people tends to increase.

- Further investigation revealed a significant response for number of daily positive cases of Covid-19 from parks, transit stations, and workplaces.

- Using the **Negative Binomial Regression** we were able to create a regression model that describes the relation of mobility activities that affect the number of daily positive cases of Covid-19 in 2022

