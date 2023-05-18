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

Related data is in the [cleaning](https://github.com/RimpleDabas/Rental-Market-Analysis-Project-one/tree/main/Cleaning%20and%20merging%20coding%20files) and merging folder and subfolders for each type of dataset : respective cleaning .ipynb [files](https://github.com/RimpleDabas/Rental-Market-Analysis-Project-one/blob/main/Cleaning%20and%20merging%20coding%20files/Datasets%20Cleaned%20and%20original_Average%20rents/Average_rents_cleaned.ipynb) are commented for further instructions. Script includes function for easy automation and can be used to clean any datasets downloaded using above links in.csv format.The function "CleanData' takes input for the file path and the corresponding year and will return data in the clearn format required for visualization.

## **Data Visualization**

The script files for data visualisation are in Visualization [coding] (https://github.com/RimpleDabas/Rental-Market-Analysis-Project-one/blob/main/Visualization%20Coding%20files/Boxplot_IQR_calculation_Rimple.ipynb) files. Most of them use function to make the process easier. These are commented for better understanding. For e.g. boxplot_loop script contains function data_set with four inputs(Path,year,province and column) and can be used to visualize plot for any province,year and any column.

## **Plots and figures**

The folder with the name [Plots_and_summary](https://github.com/RimpleDabas/Rental-Market-Analysis-Project-one/tree/main/Plots_and_summary) contains all the results and visualizations.The folders are named by according to the type of graph used for visualization

## **Analysis**

Analysis for the visualzations and conclusions are in .pptx [file](https://github.com/RimpleDabas/Rental-Market-Analysis-Project-one/blob/main/Rental%20Analysis%20Project.pptx)

## **Observations**

In general, the y/y rent increases across  Canadian provinces have been relatively modest over the period from 2018 to 2022, with most provinces experiencing increases of less than 10% per year ![line graph](/Plots_and_summary/Lucy_Bar%20and%20line%20graphs/YOY%20average%20rent%20change.png).


British Columbia and Ontario have experienced more moderate increases in rent over the same period, with growth rates ranging from 2.8% to 6% per year. Despite the moderate increase, these provinces continue to have some of the highest average rent prices in the country. The factors influencing this could be higher net Migration and Mortgage rates.

Within Ontario average rents have been consistently increasing with Toronto being at the highest over the period of 2018-2022 only exception being constant during 2020-2021. We are assuming this to be the effect of Covid pandemic![Ontario](/Plots_and_summary/Rimple_box%20plots%20and%20linear%20regression/Line%20graphs/Average%20Rents%20trend%20Ont..png).

Vacancy Rates and Average rents have mild negative correlation. We cannot conclude with certainty that increase in one of them has significant impact on another. For better visualization we need to remove the outliers from our datasets![LR](/Plots_and_summary/Rimple_box%20plots%20and%20linear%20regression/Linear%20and%20scatter%20plots/Linear%20regression%20Plot%20-%20%20Average%20Rents%20vs%20Vacancy%20Rates%20(%20Central%20Toronto).png).


## **Contributors**
Data research – Rimple

Data Cleaning – Sweta ,Kerry ,Rimple

Data merging – Rimple

Data Visualization – Sweta, Sakshi, Lucy, Abisola, Kerry, Rimple

Data Analysis - Sweta, Sakshi, Lucy, Abisola, Kerry, Rimple

API - Sweta

Presentation - Rimple
