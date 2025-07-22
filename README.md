# Crime-Data-Analysis
Visualizing and Analyzing Crime Trends in Los Angeles (2020–Present) This project uses public crime data from the Los Angeles Police Department to analyze, visualize, and animate crime patterns across time and locations. It explores trends by date, area, and crime type using Python-based data science and visualization tools.
# Crime Data Analysis: Los Angeles (2020–Present)

## Overview

This project analyzes crime data reported by the Los Angeles Police Department from 2020 to the present. It focuses on exploring crime patterns across time, locations, and crime types using Python. Key goals include:

- Identifying trends in crimes over time
- Detecting areas most prone to specific crimes
- Visualizing crime frequency through heatmaps, line plots, and animations
- Offering a dynamic, data-driven understanding of crime hotspots

---

##  Dataset

- **Name**: `Crime_Data_from_2020_to_Present.csv`
- **Source**: https://data.lacity.org/api/views/2nrs-mtv8/rows.csv?accessType=DOWNLOAD
- **Columns Used**:
  - `DATE OCC` (date of crime occurrence)
  - `Premis Desc` (description of crime location)
  - `Crm Cd Desc` (crime type description)
  - `AREA NAME` (area where crime occurred)

---

## 📘 Notebook

- **Filename**: `Crime_Data_from_2020_to_Present_project.ipynb`
- **Key Features**:
  - Data cleaning and preprocessing
  - Grouping and aggregating data by location and date
  - Heatmaps of crime type vs. location
  - Line plots showing trends over time
  - Animated bar plots showing crime patterns by month and area

---

## 📌 Technologies Used

- **Python 3.x**
- **Pandas** – Data wrangling
- **Seaborn & Matplotlib** – Static visualizations
- **Plotly Express** – Interactive and animated charts
- **Jupyter Notebook** – Analysis workflow

---

## Example Visualizations

-  Heatmap of crime types by premises
-  Line plot of crime count trends over months
-  Animated bar chart: Crime frequency over time by area

---

##  How to Run

1. Clone the repository or download the notebook and dataset.
2. Ensure the following Python packages are installed:
   ```bash
   pip install pandas seaborn matplotlib plotly
