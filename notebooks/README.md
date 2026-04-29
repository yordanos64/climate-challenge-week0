# 📓 Notebooks Documentation

This folder contains the core analysis notebooks for the climate project.



 🔎 Task 2: Exploratory Data Analysis (EDA)

File: `climate_data_eda.ipynb`

Description

This notebook focuses on understanding, cleaning, and preparing the dataset.

Key Steps

* Loaded climate data from five countries
* Replaced invalid values (`-999` → NaN)
* Removed duplicates and handled missing data
* Converted `YEAR` and `DOY` into Date format
* Extracted Month for seasonal analysis

Visualizations

* Temperature trends (T2M)
* Precipitation patterns
* Correlation heatmap



🌍 Task 3: Cross-Country Analysis

File:`cross_country_analysis.ipynb`

 Description

This notebook performs comparative analysis across countries and generates insights.



* Merged all country datasets
* Conducted extreme heat analysis
* Performed One-Way ANOVA
* Built vulnerability ranking



Key Findings

* Sudan shows extreme heat stress
* Nigeria and Tanzania show rainfall variability
* Ethiopia and Kenya show moderate climate conditions
* Statistical testing confirms significant differences



📌 Summary

* Task 2 → Data understanding and preprocessing
* Task 3 → Comparative analysis and decision-making

These notebooks together provide a complete climate analysis workflow.
