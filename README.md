# WHO Covid_19 Analysis Report 
1. [Project Overview](#project-overview)
2. [Data Source](#data-source)
3. [Tools Used](#tools-used)
4. [Data Preparation and Data Cleansing](#data-preparation-and-data-cleansing)
5. [Data Analysis](#data-analysis)
6. [Visualization on Power-BI](#visualization-on-power-bi)
7. [Observations](#observations)
8. [Limitation](#limitation)

## Project Overview
The aim and objective of this WHO Covid_19 analysis is to provides comprehensive and timely information about the covid-19 pandemic. By analyzing the WHO Covid_19 dataset, we tend to uncover the trend of it"s cases across all the WHO regions internationally, discover it" rate and effect in different countries across all regions, it<s reported cases to it<s death coverage. Also by doing this analysis, we uncover the countries with the most recent cases recorded on Covid_19 by WHO. Succinctly, this analysis would tend to show a more clearer description and coverage of Covid_19 cases and death rate even in unknown regions and locations.

The WHO Regions and data that encomasses the WHO Covid_19 dataset are written below:

*Data Description*
WHO Region
- Africa (AFR)
- Americas (AMR)
- South-East Asia (SEAR)
- European (EUR)
- Eastern Mediterranean (EMR)
- Western Pacific (WPR)
  
*Covid_19 cases parameters*
Cumulative Totals
- Cases: Total number of confirmed COVID-19 cases
- Deaths: Total number of COVID-19-related deaths
Newly Reported Cases
- Last 7 Days: Number of new cases reported in the last 7 days
- Last 24 Hours: Number of new cases reported in the last 24 hours
Population-Adjusted Metrics
- Cases per 100,000 population (cumulative)
- Cases per 100,000 population (last 7 days)
Death Metrics
- Deaths (cumulative)
- Deaths per 100,000 population (cumulative)

## Data Source
The primary dataset utilized for this analysis was gotten from the "WHO-COVID-19-Global-Table-Data.csv" file, comprising comprehensive Covid_19 occurences in all regions in the world data, which are essential for the WHO Covid_19 analytics project.

## Tools Used
MS-Excel: To clean and prepare the data for analysis.
MySQL Workbench: To analyze the data.
PowerBI Desktop: To visualize the outcomes of the analysis.

## Data Preparation and Data Cleansing
- Database Creation: Concocted a database named "WHO Covid_19".
- Open Data: Opened the "WHO-COVID-19-Global-Table-Data.cs" file on MS-Excel.
- Clean Data: Used the "Proper Function" to properly arrange all colums in the dataset, used "Ctrl+b" to bold all headings, Used the "Wrap text Function" to be able to view all headings at ones.
- Blank spaces filling: Select the worksheet by "dragging your mouse" across the worksheet, Select "Ctrl+G", select "Special", Click to select "blanks" and then "OK", Manually fill what you want to write in the blank spaces (for example; "N/A") , and finally press "Ctrl + enter" on the keyboad to auto fill all blanks.
- Handle Special Characters: Select "ctrl+H" to find and replace all special characters
- Ensure Data Integrity: Validate data integrity and consistency throughout the process.

## Data Analysis
Questions Answered in Data Analysis Process are atached in SQL Queries 
- Identify all data insights in WHO Covid_19 dataset per WHO Regions
- Outline all the Names of Countries that starts with letter “A”
- Showcase how to use the “OR” to retrieve information in a dataset
- Using a “parenthesis” instead of an “OR” statement, retrieve data from few countries in the Covid_19 dataset
- Extract information on other countries not including the previous question as written above
- Determine the Covid_19 cases and death cases newly reported in the last 7 days by WHO in Africa, particularly Nigeria
- Write a query to extract all distinct WHO Regions in the dataset
- Write a query to determine the Covid_19 cases cumulative total less than or equals to 500000
- Determine the Top 10 countries with all WHO Covid_19 Parameters
- Calculate the total sum of Covid_19 cases reported by WHO and name it as “Total cases” from the dataset
- Determine the top 10 countries that have a cumulative total cases recorded between 500000 and 1000000
- Extract all cumulative total covid_19 cases recorded per WHO Region
- Determine the Number and Names of countries in Africa that recorded a cumulative total cases greater than 10000
- Determine the top 5 countries in Africa that recorded the highest cumulative death cases on covid_19 
- Determine the top 5 countries in Americas that recorded the highest cumulative death cases on covid_19
- Determine the top 5 countries in Europe that recorded the highest cumulative death on covid_19 cases
- Determine the sum of the top 10 cases newly recorded in last 7 days and last 7 days per 100000 population and last 24 hours in Africa as a WHO Region 
- Write a query to extract the top 10 total cumulative cases and total cumulative death in Africa and Americas 
- Write a query to extract the top 10 total cumulative cases and total cumulative death in Western Pacific region
- Write a query to extract the top 10 total cumulative cases and total cumulative death in South-East Africa

 Note: Data cleaning and data analysis SQL files are attached for reference.

## Visualization on Power_BI
- After completing data cleaning on MS-Excel, the results were exported MySQL for further analysis in a CSV files.
- This CSV file served as the basis for creating a visually captivating dashboard in Power-BI.
- The objective of this Power BI visulization dashboard was to provide a wholesome comprehension and channeling of adequate information on the outcomes derived from the SQL data analysis.
- It's also crucial to note that the Power BI visualization dashboard created is passive one; it was purposely designed to visually representing the insights obtained from  MySQL data analysis.

## Observations
It was found out that in the analysis that:
- WHO recorded Covid_19 cases in a total of 8 regions consisting of 6 known regions (Americas, Africa, Europe, South-East Asia, Eastern Mediterrainian, Western Pacific) and 2 unknown regions (Other and Non-Available).
  WHO recoreded Covid_19 cases in a total of(238) including (237) known countries and (1) other unknown country across the world
  WHO also recorded a total of the following:
  Covid_19 Cases - cumulative total = 1125344648
  Covid_19 Cases - cumulative total per 100000 population = 4049343.815
  Covid_19 Cases - newly reported in last 7 days = 12773008
  Covid_19 Cases - newly reported in last 7 days per 100000 population = 56342.47161
  Covid_19 Cases - newly reported in last 24 hours = 1990708
  Covid_19 Deaths - cumulative total = 12735586
  Covid_19 Deaths - cumulative total per 100000 population = 27322.63455
  Covid_19 Deaths - newly reported in last 7 days = 22774
  Covid_19 Deaths - newly reported in last 7 days per 100000 population = 70.20708944
  Covid_19 Deaths - newly reported in last 24 hours = 3490
- It was discovered in the analysis that Global had the highest Covid_19 Cases - cumulative total recorded and Covid_19 Deaths - cumulative total with a figure of (562672324) and (6367793) repectively while Democratic People'S Republic Of Korea, Saint Helena, Tokelau, Turkmenistan had the least or no case reorded nor death recorded.

## Limitation
- Exclusion of "others" and "Non-Available" (N/A) cells: During the analysis process, a total of (2) others and (85) Non-Availables cells were identified with no specific data records and all these were excluded from the analysis done in other to ensure quality, traceable and reference-able data analysis 













