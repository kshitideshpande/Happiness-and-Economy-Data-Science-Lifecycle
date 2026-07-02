# Happiness & Economy Analysis (2020–2024)

Exploring the relationship between global happiness and economic indicators using data from the World Happiness Report and World Bank GDP per capita across 5 years.

🌍 **Interactive map:** [kshitideshpande.github.io/Happiness-and-Economy-Data-Science-Lifecycle](https://kshitideshpande.github.io/Happiness-and-Economy-Data-Science-Lifecycle/)

---

## What it covers

A full data science lifecycle — data collection, cleaning, EDA, hypothesis testing, and ML modeling — applied to a real-world dataset spanning 150+ countries from 2020 to 2024.

- Merges World Happiness Report data with World Bank GDP per capita
- Exploratory analysis with correlation heatmaps, distributions, and country-level trends
- Hypothesis testing: Pearson correlation and ANOVA across income groups
- Linear Regression and Random Forest models for happiness score prediction
- Interactive Folium world map of happiness scores by country

---

## Key findings

- GDP per capita has the strongest positive correlation with happiness scores across all years
- Social support and healthy life expectancy are the next most significant contributors
- Generosity shows no statistically significant relationship with happiness
- Random Forest feature importance confirms GDP as the dominant predictor, followed by social support

---

## Stack

- **Data:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn, Folium
- **Modeling:** Scikit-learn (Linear Regression, Random Forest)
- **Environment:** Jupyter Notebook

---

## Data sources

- [World Happiness Report 2020–2024](https://worldhappiness.report/)
- [World Bank Open Data — GDP per capita](https://data.worldbank.org/)

---

## Run locally

```bash
git clone https://github.com/kshitideshpande/Happiness-and-Economy-Data-Science-Lifecycle
cd Happiness-and-Economy-Data-Science-Lifecycle
pip install pandas numpy matplotlib seaborn scikit-learn folium jupyter
jupyter notebook Final_Tutorial_Project_Kshiti_Deshpande.ipynb
```
