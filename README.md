# Auto Accident Analysis

![Dashboard Preview](Auto%20Accident%20Dataset%20January%202020.png)

## Overview

Analyze nationwide automobile accident data to identify trends in injuries, alcohol involvement, weather conditions, and regional differences. The project combines Python, Tableau, and statistical analysis to uncover patterns that may help improve roadway safety and inform decision-making.


## Project Objectives
- Clean and prepare accident data for analysis
- Explore injury trends across U.S. regions
- Evaluate the impact of alcohol involvement
- Identify environmental factors contributing to accidents
- Create interactive Tableau dashboards
- Communicate findings through data storytelling


## Dataset

Source: ## Dataset

The dataset used in this project was provided as a course resource for academic purposes. The original source was not identified in the course materials.

A copy of the dataset used for this analysis is included in this repository (`im310_v4_wk2_auto_accident_dataset.analysis.csv`).

> **Note:** This project was completed as part of a university data analytics course. The analysis, data cleaning, statistical evaluation, and visualizations are my own work.

The dataset contains records of motor vehicle accidents, including variables such as:

- State
- Region
- Number of Injuries
- Alcohol Involvement
- Weather Conditions
- Light Conditions
- Urban/Rural Classification

## Technologies Used
### Tool  ->	Purpose
- Python  ->  Data cleaning and statistical analysis
- Pandas  ->  Data manipulation
- NumPy  ->  Numerical calculations
- Matplotlib  ->  Visualizations
- Tableau Public  ->  Interactive dashboards
- Excel  ->  Initial data preparation

## Data Cleaning

Several preprocessing steps were performed before analysis:

- Removed invalid injury codes (98 and 99)
- Corrected duplicate weather condition columns
- Enumerated coded categorical variables
- Filtered unknown alcohol values when appropriate
- Checked for missing values and outliers
- Standardized regional classifications


## Exploratory Data Analysis

The analysis examined:

- Total accidents by region
- Injury rates
- Alcohol-related crashes
- Urban vs. Rural accidents
- Weather conditions
- Injury severity distributions
- Regional comparisons


## Statistical Analysis

Descriptive statistics included:

- Mean
- Median
- Standard Deviation
- Quartiles
- Range


## Outlier detection

Python was used to calculate summary statistics and compare alcohol-related accidents against non-alcohol-related accidents.


## Tableau Dashboard

The interactive dashboard includes:

- Regional accident map
- Injury totals
- Alcohol involvement
- Injury percentages
- Weather conditions
- Filters for deeper exploration

([Tableau Dashboard](https://public.tableau.com/app/profile/tim.manuel/viz/AutoAccidentDatasetDashboard/AutoAccidentDataset))


## Key Findings

Some notable insights include:

- Alcohol-related crashes resulted in significantly more injuries on average than non-alcohol-related crashes.
- Urban areas experienced a higher average number of injuries than rural areas.
- Nearly half of crashes in the Southern region resulted in injuries.
- Unknown and missing categorical values required careful handling before analysis.
- Weather conditions influenced accident frequency but had less impact than alcohol involvement on injury severity.


## Repository Structure
Auto-Accident-Analysis/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   ├── Data_Cleaning.ipynb
│   └── Analysis.ipynb
│
├── dashboard/
│   └── Tableau_Dashboard.twbx
│
├── images/
│   ├── dashboard.png
│   └── charts/
│
├── report/
│   └── Data_Model_Analysis.pdf
│
├── requirements.txt
├── README.md
└── LICENSE


## Skills Demonstrated:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Analysis
- Tableau Dashboard Design
- Python Programming
- Data Storytelling
- Business Intelligence
- Future Improvements


## Potential enhancements include:

- Predictive modeling using machine learning
- Geographic hotspot analysis
- Time-series accident forecasting
- Interactive web dashboard
- Additional demographic analysis


# Author

## Tim Manuel

Data Analytics and Data Science Portfolio
([Github](https://github.com/HalfwayBubble76))
([LinkedIn](https://www.linkedin.com/in/timothy-manuel-a70112149/))
