# Air Quality EDA — Average PM2.5 by City & Month

**Short description**  
Exploratory data analysis of PM2.5 air pollution using the `city_day.csv` (Kaggle). This project cleans data, computes monthly averages, and visualizes trends and hotspots using a line chart, heatmap, and boxplots.

---

## 🔗 Dataset
Source: *Kaggle - Air Quality Data in India*  
Link: https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india  
*(I included a small sample `data/city_day_sample.csv`. The full dataset is available at the Kaggle link above.)*

---

## 🛠 Tools
- Python (pandas, matplotlib, seaborn)
- Jupyter / Google Colab

---

## 🚀 What I did
1. Cleaned and standardized column names.  
2. Parsed `Date` to datetime and extracted month.  
3. Calculated average PM2.5 per `city` × `month`.  
4. Plotted:
   - Monthly trend line for top cities
   - Heatmap of average PM2.5 (city vs month)
   - Distribution (boxplot) by city

---

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
