# COVID-19 Data Analysis Project

This project involves analyzing a dataset of COVID-19 cases to extract meaningful insights, visualize trends, and understand the global and regional impact of the pandemic. The analysis focuses on confirmed cases, deaths, and recoveries across different regions.

---

## Table of Contents
1. [Overview](#overview)
2. [Technologies Used](#technologies-used)
3. [Dataset Description](#dataset-description)
4. [Key Analysis Steps](#key-analysis-steps)
5. [Visualizations](#visualizations)
6. [How to Run the Project](#how-to-run-the-project)
7. [Insights](#insights)
8. [Future Scope](#future-scope)

---

## Overview
The COVID-19 pandemic has impacted the world in unprecedented ways. This project leverages a dataset to analyze the distribution and trends of cases (confirmed, deaths, recovered) globally and regionally. The project includes:
- Data cleaning and preprocessing.
- Descriptive and comparative analysis.
- visualizations to highlight key patterns.

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - `pandas` for data manipulation
  - `matplotlib` and `seaborn` for data visualization

---

## Dataset Description
The dataset contains the following columns:
- **Date**: The date of data recording.
- **Region**: The country or region where the data was recorded.
- **Confirmed**: The total number of confirmed cases.
- **Deaths**: The total number of deaths recorded.
- **Recovered**: The total number of recovered cases.

**Note**: The dataset has missing values for the `State` column, which were not relevant for this analysis.

---

## Key Analysis Steps
1. **Data Cleaning**:
   - Checked for missing values and visualized null data using a heatmap.
   - Filtered out records where the number of confirmed cases was less than 10.
   
2. **Descriptive Analysis**:
   - Total confirmed, death, and recovery cases for each region.
   - Identified regions with maximum confirmed cases and minimum deaths.

3. **Sorting and Filtering**:
   - Sorted data by recovered cases in descending order.
   - Extracted COVID-19 statistics specifically for India.

4. **Enhanced Visualizations**:
   - Bar plot showing the top 10 regions with the highest confirmed cases.
   - Pie chart showing the distribution of total cases (confirmed + deaths + recovered) for the top 5 regions.

---
