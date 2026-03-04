# BRFSS Mental Health Risk Analysis

## Project Overview
This project analyzes mental health indicators from the CDC Behavioral Risk Factor Surveillance System (BRFSS) dataset. The analysis focuses on identifying patterns in anxiety and depressive disorder symptoms across demographic groups and states.

The study applies exploratory data analysis, segmentation analysis, and aggregation analysis using Python.


## Dataset
Dataset Source: CDC Behavioral Risk Factor Surveillance System (BRFSS)

Main Columns Used:
- Indicator
- Group
- State
- Subgroup
- Phase
- Time Period
- Time Period Label
- Time Period Start Date
- Time Period End Date
- Value


## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook


## Project Workflow


### 1. Data Collection
The dataset contains mental health indicators related to anxiety and depressive disorder symptoms across multiple population groups and states.

### 2. Data Cleaning
- Removed unnecessary statistical columns
- Handled missing values
- Converted date columns to datetime format
- Filtered relevant segmentation categories

### 3. Segmentation Analysis
Analysis performed across:
- Age groups
- Gender groups
- Geographic regions (states)
- Time trends

### 4. Aggregation Analysis
Data aggregation was performed to compute:
- Average health risk by state
- Average risk by indicator
- Maximum and minimum health risk values


## Key Insights
- Mental health symptoms vary significantly across demographic groups.
- Certain states show higher average mental health risk values.
- Younger age groups tend to report higher anxiety and depressive symptoms.
- Trends over time indicate fluctuations in mental health conditions during different phases.
