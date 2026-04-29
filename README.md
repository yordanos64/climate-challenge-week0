 🌍 African Climate Trend Analysis – Week 0

 Project Overview

This project analyzes climate trends across five African countries using **NASA POWER climate data (2015–2026)**.

Countries included:

* Ethiopia
* Kenya
* Nigeria
* Sudan
* Tanzania

 Objectives

* Perform Exploratory Data Analysis (EDA)
* Identify climate patterns (temperature, precipitation, humidity)
* Compare countries using statistical analysis
* Support climate insights for policy discussions (COP32 context)



 Current Progress

* Established full project structure
* Configured CI/CD workflow (GitHub Actions)
* Completed data ingestion for all five countries
* Performed EDA (Task 2)
* Conducted cross-country analysis (Task 3)

 📂 Project Structure

```bash
climate-challenge-week0/
│
├── Data/
│   ├── ethiopia.csv
│   ├── kenya.csv
│   ├── nigeria.csv
│   ├── sudan.csv
│   └── tanzania.csv
│
├── notebooks/
│   ├── climate_data_eda.ipynb
│   ├── cross_country_analysis.ipynb
│   └── README.md
│
├── scripts/
├── src/
├── tests/
├── .github/workflows/
│
├── README.md
├── requirements.txt
└── .gitignore


 📓 Notebooks

Detailed notebook explanations are available here:
👉 `notebooks/README.md`



 Key Results

Temperature

* Sudan → hottest country
* Ethiopia → coolest country

 🌧️ Precipitation

* Nigeria & Tanzania → high rainfall variability

 Statistical Analysis

* One-Way ANOVA applied
* **P-value = 0.0 → Significant climate differences**



 Vulnerability Ranking

1. Sudan → Extreme heat stress
2. Nigeria & Tanzania → Rainfall variability
3. Ethiopia & Kenya → Moderate climate stress

 🛠️ Tools & Technologies

* Python 3.13.7
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

 ▶️ Setup Instructions

```bash
git clone https://github.com/yourusername/climate-challenge-week0.git
cd climate-challenge-week0
pip install -r requirements.txt
jupyter notebook
```



 Limitations

* Missing data handling may affect accuracy
* Satellite data may not reflect micro-climates
* Analysis limited to five countries


Future Work

* Expand to more African countries
* Apply machine learning models
* Build interactive dashboards



👤 Author

 Yordanos Nius
Aspiring Full-Stack & AI Engineer

GitHub: https://github.com/yordanos64



 Conclusion

This project highlights **significant climate variability across African regions**, with Sudan identified as a critical heat-risk zone. The findings provide valuable insights for **climate policy discussions and adaptation strategies**, especially for Ethiopia’s COP32 engagement.
