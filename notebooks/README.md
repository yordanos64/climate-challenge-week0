 Exploratory Data Analysis (EDA) Notebooks

This folder contains the primary analysis conducted for each country.

 Files
- `climate_data_eda.ipynb`: The main notebook where data from all five countries is merged, cleaned, and visualized.

## Analysis Steps (Task 2)
1. Data Loading:Merged separate CSVs for Ethiopia, Kenya, Nigeria, Sudan, and Tanzania.
2. Data Cleaning:
   - Replaced NASA sentinel values (`-999`) with `NaN`.
   - Handled missing values and dropped duplicate rows.
3. **Feature Engineering:
   - Converted `YEAR` and `DOY` into a proper `Date` format.
   - Extracted `Month` for seasonal analysis.
4. Visualizations:

   - Temperature Trends (T2M): Identified Sudan as the hottest and Ethiopia as the coolest.
   - recipitation Patterns: Visualized rainfall peaks for each country.
   - Correlation Heatmap: Analyzed the relationship between variables like humidity, pressure, and temperature.




 $$$ Task 3: Cross-Country Analysis & Vulnerability Ranking

This section synthesizes data from Ethiopia, Kenya, Nigeria, Sudan, and Tanzania to support Ethiopia's COP32 position.

 🔍 Key Analysis Steps
*   Data Merging:Integrated 20,540 rows of daily observations into a unified dataset.
*   Extreme Heat Analysis: Identified Sudan as a critical hotspot with an average of 224.5 days/year** exceeding 35°C.
*   Statistical Testing: Conducted a One-Way ANOVA , resulting in a P-value of 0.0, confirming significant climate variation across the region.

 🏆 Vulnerability Ranking
1. Sudan (Extreme Heat Stress)
2. Nigeria/Tanzania (High Rainfall Variability)
3.Ethiopia/Kenya (Moderate Climate Stress)


