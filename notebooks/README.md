 Exploratory Data Analysis (EDA) Notebooks

This folder contains the primary analysis conducted for each country.

 Files
- `climate_data_eda.ipynb`: The main notebook where data from all five countries is merged, cleaned, and visualized.

## Analysis Steps (Task 2)
1. **Data Loading:Merged separate CSVs for Ethiopia, Kenya, Nigeria, Sudan, and Tanzania.
2. **Data Cleaning:
   - Replaced NASA sentinel values (`-999`) with `NaN`.
   - Handled missing values and dropped duplicate rows.
3. **Feature Engineering:**
   - Converted `YEAR` and `DOY` into a proper `Date` format.
   - Extracted `Month` for seasonal analysis.
4. Visualizations:**
   - Temperature Trends (T2M): Identified Sudan as the hottest and Ethiopia as the coolest.
   - recipitation Patterns: Visualized rainfall peaks for each country.
   - Correlation Heatmap: Analyzed the relationship between variables like humidity, pressure, and temperature.
