# Rental Analysis : Canada

![Reference Image](/Plots_and_summary/Sweta_line_bar_API/Canada.png)

##  **Main Objectives and questions to answer**
### **Overview of Rental Market Trends from 2018 to 2022**

What were the major trends in average rents, number of units, and vacancy rates during this period across Canada?

Y/Y percentage change in Average rent during this period

Rental Market Analysis for the year 2022

How do average rents and vacancy rate vary across provinces in Canada?

How does the location impacts average rents between  cities in Ontario and neighbourhoods in Toronto?

Is there any  relation between average rents and vacancy rates between cities in Ontario and neighbourhoods in Toronto

To overlay our rental data location wise across Canada and Ontario using API and geo views

## **Data extraction/cleaning and merging**

The data for the analysis was collected from Canada Mortgage and Housing Corporation (CMHC) can be found here :

<https://www.cmhc-schl.gc.ca/en/professionals/housing-markets-data-and-research/housing-data/data-tables/rental-market/urban-rental-market-survey-data-average-rents-urban-centres>

<https://www.cmhc-schl.gc.ca/en/professionals/housing-markets-data-and-research/housing-data/data-tables/rental-market/urban-rental-market-survey-data-vacancy-rates>

<https://www.cmhc-schl.gc.ca/en/professionals/housing-markets-data-and-research/housing-data/data-tables/rental-market/urban-rental-market-survey-data-number-units>

Related data can be found in cleaning and merging folder and subfolders for each type of dataset : respective cleaning .ipynb files are commented for further instructions. Script includes function for easy automation and can be used to clean any datasets downloaded using above links in.csv format

## **Data Visualization**

The script files for data visualisation can be found in Visualization coding files. Most of them use function to make the process easier. These are commented for better understanding

## **Plots and figures**

The folder with the name Plots_and_summary contains all the results and visualizations.The folders are named by according to the type of graph used for visualization

## **Analysis**

Analysis for the visualzations and conclusions can be found in .pptx file

## **Insights**

In general, the y/y rent increases across these Canadian provinces have been relatively modest over the period from 2018 to 2022, with most provinces experiencing increases of less than 10% per year.

British Columbia and Ontario have experienced more moderate increases in rent over the same period, with growth rates ranging from 2.8% to 6% per year. Despite the moderate increase, these provinces continue to have some of the highest average rent prices in the country. The factors influencing this could be higher net Migration and Mortgage rates.

Within Ontario average rents have been consistently increasing with Toronto being at the highest over the period of 2018-2022 only exception being constant during 2020-2021. We are assuming this to be the effect of Covid pandemic.

Vacancy Rates and Average rents have mild negative correlation. We cannot conclude with certainty that increase in one of them has significant impact on another. For better visualization we need to remove the outliers from our datasets.


## **Contributors**
Data research – Rimple

Data Cleaning – Sweta ,Kerry ,Rimple

Data merging – Rimple

Data Visualization – Sweta, Sakshi, Lucy, Abisola, Kerry, Rimple

Data Analysis - Sweta, Sakshi, Lucy, Abisola, Kerry, Rimple

API - Sweta

Presentation - Rimple
