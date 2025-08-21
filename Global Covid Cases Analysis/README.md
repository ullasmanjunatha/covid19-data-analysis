# Global COVID-19 Cases Analysis

## Overview

This project provides a comprehensive analysis of global and US-specific COVID-19 data, focusing on confirmed cases, deaths, recoveries, and related percentages by country and state/province. The analysis involves cleaning, aggregating, and visualizing large time-series datasets to understand the pandemic's impact across regions.

---

## Data Sources

- Kaggle dataset - COVID-19 data from John Hopkins University
- Global confirmed cases and deaths data with daily cumulative counts for countries worldwide.
- Detailed US state- and county-level data for confirmed cases, deaths, recoveries, and related metrics.
- Processed datasets include cleaned and aggregated CSV files ready for analysis.

---

## Project Structure

- **Data Cleaning Notebooks**: Scripts for removing irrelevant columns, handling missing data, and aggregating data at country/state levels.
- **Merged Data Files**: Combined datasets containing total confirmed cases, deaths, recovered cases, recovered percentage, and death percentage.
- **Visualization Notebooks**: Code to generate bar charts and  scatter plots to visualize COVID-19 trends by region.
- **Processed CSV Files**: Data tables such as `Visualization_Ready.csv`, clean global datasets on confirmed cases and deaths, and US-specific cleaned data.

---

## Key Analysis and Findings

- Aggregated confirmed cases and deaths show significant variation between countries and US states, reflecting differences in outbreak scale and healthcare responses.
- Recovery percentages are generally very high (>95%) in most regions, suggesting effective recovery among infected individuals.
- Death percentages vary considerably across locations, highlighting differing impacts and possible areas for public health focus.
- Visualizations like scatter plots and bar charts reveal strong positive correlations between confirmed and recovered cases.
- Top affected US states such as California, Texas, and Florida have the highest total counts but also high recoveries.

---

## Usage Instructions

1. Load cleaned data files (`Visualization_Ready.csv`, `clean_global_confirmed_cases.csv`, etc.) into Jupyter notebooks.
2. Run data aggregation and merging cells to prepare datasets for analysis.
3. Execute visualization code snippets to generate insights through plots.
4. Modify and extend code for customized analysis or to include newer data.

---

## Technologies Used

- Python 3.x
- Pandas for data manipulation
- Matplotlib and Seaborn for visualizations
- Jupyter Notebook for interactive analysis

---

## How to Run

- Ensure all required CSV files and notebooks are in your working directory.
- Open notebooks in JupyterLab or Jupyter Notebook environment.
- Install required packages via pip if needed (`pandas`, `matplotlib`, `seaborn`).
- Run cells sequentially for clean, aggregate, and visualize COVID-19 data.

---

## Conclusion

This analysis provides valuable insights into the COVID-19 pandemic's regional impacts, recovery efficiency, and mortality variations. It serves as a resource for further study and decision-making support in public health and epidemiology.

---

