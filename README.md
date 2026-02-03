# CIVE 202 – Project #1: Organizing and Summarizing Air Quality Data

**Client:** UNMC Water, Climate and Health Group  
**Course:** CIVE 202 – Civil Engineering  

## Project Overview
This project analyzes air quality data collected from AirPurple sensors across Nebraska between February 2024 and March 2025. The purpose of this analysis is to help the UNMC Water, Climate and Health Group understand air quality conditions, identify potential pollution hotspots, and evaluate possible public health concerns.

## Data Source
The data used in this project were provided as part of the course assignment and originate from AirPurple community air quality monitors deployed across Nebraska. The raw CSV data file is included in this repository to ensure reproducibility.

## Methods
The analysis was completed using Python in a Jupyter Notebook environment. The pandas library was used to load, organize, and analyze the dataset. Summary statistics were calculated for volatile organic compounds (VOC), particulate matter less than 2.5 microns (PM2.5), and particulate matter less than 10 microns (PM10). Data were grouped by sensor location, temperature and humidity, and sensor altitude.

## Repository Contents
- `Project1_AirQuality_Analysis.ipynb` – Jupyter Notebook containing all Python code used in the analysis  
- `AirQuality_Daily_StudentVersion.csv` – Raw air quality data file used in the analysis  
- `README.md` – Project description and repository overview  

## Notes
All results in this repository are reproducible using the provided Jupyter Notebook and raw data file.
