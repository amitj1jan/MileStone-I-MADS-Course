# Causality & Mitigations - Analysis of NYC accidents
**Authors:** Amit Jha and Sahil Pujari

This repository contains the project report for the SIADS 591 Milestone I Project, titled "Causality & Mitigations - Analysis of NYC accidents" by Amit Jha and Sahil Pujari. The project aims to analyze factors contributing to accidents in the city of New York and propose strategies for mitigation using data science techniques.

## Motivation
The high number of road accidents and fatalities worldwide, including in India, motivated the authors to explore the causes of accidents in New York City. With the power of data science, they aimed to study the factors contributing to accidents and suggest strategies for reducing them.

## Data Sources
The project utilizes public datasets, including:

- **NYC Open Data:** Provides crash, vehicle, and person data for accidents reported between 2015 and 2019.
- **Traffic Speed Data:** Obtained from the NYC REAL TIME TRAFFIC SPEED DATA FEED(ARCHIVED) provided by data.βetaNYC.
- **Hospitals Locations:** Shapefile dataset from Homeland Infrastructure Foundation-Level Data (HIFLD) that provides hospital location details.
- **Traffic Volume:** Dataset containing traffic volume counts collected by the Department of Transportation (DOT) for different roadways at different times of the day.
- **Population:** Two population datasets, including USA population data and US population by ZIP code from the 2010 US decennial Census.
- **Driving Cost:** Self-compiled dataset using data from a global news and lifecycle publication, INSIDER.
- **Traffic Related Death Rate by Countries:** Dataset providing traffic-related death rates for various countries from the WHO Global Status Report on Road Safety 2018.

## Data Manipulation Methods
The authors applied various data manipulation methods to preprocess and combine the datasets effectively. These methods include assigning appropriate data types, decoding polyline fields, merging datasets based on common columns, and computing average daily traffic volume.

## Analysis and Visualizations
The project focuses on answering several questions related to traffic crashes/fatalities. Some of the key findings and visualizations include:

- Identifying the most common causes of traffic crashes in New York.
- Investigating the correlation between driving skill (proxied by license cost) and crashes/injuries.
- Analyzing the relation between traffic count/time and accidents for each ZIP code.
- Examining the relation between traffic speed/time and accidents for each ZIP code.
- Assessing the proximity of hospitals to crash sites and suggesting areas for improvement.
- Exploring the relation between traffic volume and crashes.
- Investigating the relation between traffic speed and crashes at different road segments.
- The project provides recommendations based on the findings and suggests measures such as defensive driving education, adopting best practices from countries with low traffic-related fatalities, installing crash avoidance systems, analyzing driver license status, and improving hospital coverage near crash sites.

### References
The project report includes references to relevant sources, including the World Health Organization's reports on road safety and other publications.

- Please refer to the full project report for detailed information on the methodology, analysis, visualizations, and recommendations.
https://storymaps.arcgis.com/stories/bd7e45b6ae874c45a3642ca2632a8a19
