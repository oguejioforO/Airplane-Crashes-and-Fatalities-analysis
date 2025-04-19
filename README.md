# Airplane Crashes and Fatalities Analysis

## Table of Content

- [Project Overview](#Project-Overview)
- [Dataset Info](#Dataset-Info)
- [Tools Used](#Tools-Used)
- [Data Cleaning](#Data-Cleaning)
- [Analysis Objectives](#Analysis-Objectives)
- [Results](#Results)
- [Visualizations Used](#Visualizations-Used)
- [Limitations](#Limitations)
- [Recommendations](#Recommendations)
- [Conclusion](#Conclusion)

### Project Overview
The aim of this project is to analyze historical airplane crash data to uncover patterns in fatality rates, high-risk aircraft, and common crash locations. This can support discussions around airline safety, aircraft engineering, and policy-making in the aviation industry.

### Dataset Info
- Source: The dataset highlights Boeing 707 accidents and other airplane crashes globally from 1948 to 2015.

- Key Columns:

   - Date, Time, Location, Operator, Flight, Route

   - Type, Registration, cn/In, Aboard, Fatalities, Ground, Summary

   - Size: 5,268 crash records
   - Fatalities: 105,587
   - Aboard: 144,837
   - Fatality Rate: 73%
This dataset provides comprehensive data for aviation analysis and safety research.

### Tools Used
- Microsoft Excel – for data cleaning and dashboard creation

### Data Cleaning
- Data cleaning was carried out in Excel before importing into Power BI. Steps included:

- Handling missing values in columns like Summary, Flight #, and Ground

- Removing duplicate rows

- Normalizing text cases for consistency in categories like Location, Operator, and Type

### Analysis Objectives
- Examine trends in airplane crashes and fatalities over the years

- Identify top crash-prone locations and operators

- Explore which aircraft types were involved in the most fatalities

- Understand seasonal/monthly patterns in crashes

- Map fatalities geographically

- Analyze the relationship between number aboard and fatalities

### Results
- Highest fatalities occurred between 1970–1990, with a steady decline afterward

- Military aircraft and Aeroflot had the highest numbers of passengers and fatalities

- Douglas DC-3 was the most frequently involved aircraft in fatal incidents

- Most crashes occurred in Russia, the U.S., and Brazil

- Chicago, New York, and Cairo were among the top crash locations

###  Visualizations Used
- Bar charts – Top aircraft, operators, locations, and countries

- Line chart – Fatalities by year

- Column chart – Fatalities vs Aboard by month

- Stacked bar chart – Aircraft types and crash frequency

- Map – Global distribution of crash fatalities

- Slicers – Filters by Year, Month, Country, Type, Operator

### Limitations
- Missing or incomplete data in older records

- No weather or mechanical condition variables included

- Ground fatalities not always recorded

- Limited aircraft model details for some records

### Recommendations
- Extend the dataset to include post-2015 crash data for modern insights

- Include weather, technical failure, or human error information for better causal analysis

- Use advanced analytics or machine learning to predict crash probabilities

- Integrate survival rate data by aircraft and region


### Conclusion
This project explores global airplane crash data through rich visuals and analytics. It’s a valuable tool for aviation analysts, safety experts, and anyone curious about air travel safety history. 
Through Power BI’s interactive capabilities, users can easily filter and explore over 60 years of crash data in a meaningful and insightful way.

