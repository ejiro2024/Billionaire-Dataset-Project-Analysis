# Billionaire-Dataset-Project-Analysis

![Billionaire_Pix](Billionaire_Pix.jpeg)




## Table of Content

- [Project Overview](#Project-Overview)
- [Data source](#Data-source)
- [Problem Statement](#Problem-Statement)
- [Tools used](#Tools-used)
- [Skills demonstrated](#Skills-demonstrated)
- [Data Analysis](#Data-Analysis)
- [Visualisations](#Visualisations)
- [Conclusion and Recommendations](#Conclusion-and-Recommendations)
  
## Project Overview
This project explores the profiles of the world’s richest individuals using a structured dataset. It includes insights into net worth by industry, country, and self-made status.
In addition, it maps macroeconomic metrics like GDP and tax rates to billionaire distribution. Visualizations are created using Excel for intuitive storytelling. The project highlights trends in wealth, economic context, and demographic influence.


## Data source
Key Columns in the Dataset include Rank & Category, Name Details, Demographics, Net Worth (in millions USD), Company Location Details and Economic Metrics by Country like

- cpi_country – Consumer Price Index
- gdp_country – GDP
- life_expectancy_country
- tax_revenue_country_country
- total_tax_rate_country
- population_country

This dataset was downloaded as a .csv file from a google drive link.
  
## Problem Statement
Despite rising global inequality, little is understood about how personal wealth among the ultra-rich aligns with broader economic conditions. This project seeks to uncover patterns in billionaire wealth by industry, geography, self-made status, and national economic indicators, helping us understand the socio-economic context behind wealth accumulation.

## Tools used
Excel

## Skills demonstrated
1. Data Cleaning, Preparation and Transformation

- Standardized Gender Values
Using Find & Replace via the Home tab > Editing > Find & Select > Replace, the values in the gender column were standardized by replacing "M" with "Male" and "F" with "Female".
- Calculated Date of Birth
A new column titled Date of Birth was created using the formula:
=DATE(birthYear, birthMonth, birthDay)
The autofill handle was used to apply this formula to the entire column.
- Inserted Current Date Column
A new column titled Current Date was inserted before the Date of Birth column. The formula =TODAY() was used to populate it and autofill was applied to the remaining rows.
- Calculated Age
Using Excel’s YEARFRAC() function, a new column was created to calculate the age:
=YEARFRAC(Date of Birth, Current Date)
This value was autofilled for all entries.
- Cleaned GDP Values
In the gdp_country column, commas were removed for numerical consistency using Ctrl + H - replacing all, with an empty string.
- Reordered Columns
The Age column was moved to appear after the population_country column using drag-and-drop with the Shift key held.
2. Data Analysis
  
3. Data Visualization
   
4. Dashboard Development

5. Data Structuring

6. Insight Generation

## Data Analysis

- Descriptive Statistics:
Descriptive statistics were performed using Excel’s Data Analysis Toolpak. The Analysis Toolpak add-in was enabled, and the dataset was analyzed by selecting “Descriptive Statistics” and checking the box for "Labels in First Row".
- Pivot Tables and Charts Created:
  1. Gender vs Count of Gender
  2. Category vs Sum of Final Worth (Top 10 Categories)
  3. Country vs Count of Last Name (Top 5 Countries)
  4. Age vs Count of Age
  5. Category vs Tax Revenue (Top 5 Categories)
  6. Category vs Tax Revenue (Bottom 5 Categories)
  7. SelfMade vs Count of SelfMade
  8. Country vs Sum of GDP

## Visualisations
A comprehensive dashboard was developed by assembling the pivot charts to allow for interactive insight into wealth, industries, and demographics.

Slicer Application:
Slicers were added via Insert > Slicer, allowing dynamic filtering by fields such as gender, country, category, and selfMade.

![GITHUB_BILLIONAIRE_EXCEL_Dashboard](GITHUB_BILLIONAIRE_EXCEL_Dashboard.Pdf)


## Conclusion and Recommendations
Based on the analysis, the following recommendations were proposed:
-	Optimize Inventory Management: Adjust stock levels based on product demand trends.
-	Improve Staffing Schedules: Allocate staff efficiently during peak sales hours.
- Targeted Promotions: Offer discounts on slow-moving products to increase sales.
- Enhance Product Offerings: Expand best-selling product lines while discontinuing low-performing items.
 visualizations:



### Back to top 
###### [Table of Content](#Table-of-Content)
