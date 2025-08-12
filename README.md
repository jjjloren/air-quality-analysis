# Air Quality EDA — Average PM2.5 by City & Month

**Short description**  
Exploratory data analysis of PM2.5 air pollution using the `city_day.csv` (Kaggle). This project cleans data, computes monthly averages, and visualizes trends and hotspots using a line chart, heatmap, and boxplots.

---

## Dataset
Source: *Kaggle - Air Quality Data in India*  
Link: https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india  
*(I included a small sample `data/city_day_sample.csv`. The full dataset is available at the Kaggle link above.)*

---

## Tools
- Python (pandas, matplotlib, seaborn)
- Jupyter / Google Colab

---

## What I did
1. Cleaned and standardized column names.  
2. Parsed `Date` to datetime and extracted month.  
3. Calculated average PM2.5 per `city` × `month`.  
4. Plotted:
   - Monthly trend line for top cities
   - Heatmap of average PM2.5 (city vs month)
   - Distribution (boxplot) by city

---

##  Key Insights
1. Delhi’s PM2.5 levels are consistently the highest among all cities in the dataset, with sharp peaks between November and January. This aligns with winter weather patterns and seasonal crop-burning in surrounding states.
2. Coastal cities such as Mumbai and Chennai maintain relatively lower PM2.5 levels year-round, likely due to stronger coastal winds dispersing airborne pollutants.
3. Distinct seasonal variation is visible: air quality generally worsens in winter months and improves in monsoon months (June–September), suggesting meteorology plays a large role in pollution control.
4. The boxplot analysis shows a wider spread of PM2.5 values in northern cities (Delhi, Lucknow) compared to southern ones, indicating more volatile pollution events in the north.
5. These findings suggest that targeted, seasonal mitigation strategies — such as stricter emission control during pre-winter months — could significantly improve air quality."

---

## Conclusion
This analysis of India’s air quality data reveals strong geographic and seasonal trends in PM2.5 pollution. Northern cities such as Delhi experience the highest concentrations, particularly during winter, while coastal cities maintain lower levels due to favorable wind patterns. The clear seasonality suggests that pollution control efforts should be intensified during high-risk months, especially in regions with historically poor air quality. These findings can guide policymakers, environmental agencies, and urban planners in developing targeted, data-driven strategies to improve public health and reduce pollution exposure.

## 📂 Repository structure
```
air-quality-analysis/
├── notebooks/
│   └── Air_Quality_EDA.ipynb
├── images/
│   ├── monthly_trend.png
│   ├── heatmap.png
│   └── city_boxplot.png
├── data/
│   └── city_day_sample.csv
└── README.md
```
