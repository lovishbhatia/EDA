
<!-- PROJECT BADGES -->
<p align="center">
  <img src="https://img.shields.io/badge/Project-Type-Data%20Analysis-brightgreen?style=for-the-badge">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge">
</p>

---

# 🎵 **Spotify Music Trends Analysis (2015–2025)**  
### _A Deep Dive into 85,000+ Tracks Using Python, EDA, and Statistical Insights_

---

## 📚 **About the Project**

This repository contains a **high-quality exploratory data analysis (EDA)** of **Spotify music trends from 2015 to 2025**, using a dataset of **85,000+ tracks**.  
It reveals **patterns, correlations, popularity trends, genre evolution**, and **audio feature analysis** across the decade.

This project is ideal for:
- 🎓 Data Science Students  
- 📊 Analysts  
- 🎧 Music Researchers  
- 🧠 ML Engineers looking for clean feature engineering baselines  
- 🗂️ Portfolio Showcases  

The EDA is built using **Python, Pandas, NumPy, Matplotlib, and Seaborn**, with detailed insights and premium visualizations.

---

## 🗂️ **Repository Structure**

```

📁 Spotify-Data-Analysis/
│
├── 📓 EDA.ipynb                     # Complete Exploratory Data Analysis
├── 📑 spotify_2015_2025_85k.csv     # Raw dataset (85k+ tracks)
├── 📄 README.md                     # Project documentation
│
└── 📁 assets/                       # Plots, screenshots, visuals (optional)

````

---

## ⭐ **Key Highlights**

### 🔍 **1. Data Cleaning & Preparation**
- Removed duplicates  
- Handled missing values  
- Normalized skewed features  
- Converted types for time-series analysis  
- Extracted new attributes for deeper insights  

### 📊 **2. Advanced Exploratory Data Analysis**
Includes more than **30+ visualizations**, such as:
- Popularity distribution and trendlines  
- Audio feature comparisons across years  
- Correlation heatmaps  
- Regression overlays for feature pairing  
- Genre-wise breakdown of feature behavior  
- Artist impact exploration  
- Tempo/energy valence emotional mapping  

### 🧠 **3. Statistical & Semantic Insights**
- Z-score outlier identification  
- Variance & standard deviation analysis  
- Percentile distribution profiling  
- Time-based popularity modeling  
- Linear regressions between key attributes  

### 🎨 **4. Visual Storytelling**
This project emphasizes **clean, modern charts**, including:
- Heatmaps  
- Pairplots  
- Scatterplots with regression lines  
- KDE density curves  
- Year-over-year line charts  
- Genre comparison bar charts  

---

## 📁 **Dataset Description**

**File:** `spotify_2015_2025_85k.csv`  
**Total Records:** ~85,000  
**Total Features:** 20+ audio and metadata fields  

| Feature | Description |
|--------|-------------|
| track_name | Name of the track |
| artist | Performing artist |
| release_year | Year of release |
| popularity | Spotify popularity index |
| danceability | Dance-friendliness (0–1) |
| energy | Track intensity (0–1) |
| valence | Mood positivity |
| acousticness | Acoustic nature |
| instrumentalness | Instrumental score |
| liveness | Audience presence indicator |
| tempo | Track speed (BPM) |
| duration_ms | Length of track |
| genre | Genre of the music |

---

## 🧭 **Project Objectives**

### 🎯 **Primary Goals**
- Analyze **year-wise music evolution** from 2015 to 2025  
- Identify **features influencing track popularity**  
- Study **genre-specific audio characteristics**  
- Compare **acoustic vs. electronic era shifts**  
- Provide **clean analytical baselines** for machine learning models  

### 🔮 **Long-Term Vision**
This project can be extended into:
- ML models (popularity prediction)  
- Genre classification systems  
- Recommendation engines  
- Interactive dashboards  

---

## 🚀 **How to Run the Project**

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
````

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

**requirements.txt**

```
pandas
numpy
matplotlib
seaborn
jupyter
scipy
```

### 3️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

Open **EDA.ipynb** and run all cells.

---

## 📊 **Sample Visualizations (from Notebook)**

You may add your actual charts in `/assets`.

```
📌 Genre-wise Tempo Distribution  
📌 Popularity Trend (2015–2025)  
📌 Audio Feature Correlation Heatmap  
📌 Energy vs Danceability (with regression line)  
📌 Emotional Mapping using Valence vs Energy  
```

---

## 🧩 **Methodology**

### 🔸 Step 1 — Importing & Understanding the Data

✔ Loaded dataset
✔ Basic info, statistics, and shape observation

### 🔸 Step 2 — Data Cleaning

✔ Handled missing values
✔ Removed non-informative entries
✔ Checked for duplicates

### 🔸 Step 3 — Feature Engineering (Optional)

✔ Created `popularity_class`
✔ Created decade buckets
✔ Normalized skewed features

### 🔸 Step 4 — Exploratory Data Analysis

✔ Visualized distributions
✔ Explored correlations
✔ Year-wise trend breakdown
✔ Genre mapping

### 🔸 Step 5 — Documented Insights

✔ Key findings noted
✔ Observations included beside each chart

---

## 🧵 **Core Insights from the Analysis**

(These will be updated as more insights are added)

* Popularity of tracks shows visible spikes in specific years.
* Energy and danceability strongly correlate with viral tracks.
* Acoustic tracks peaked around 2019–2020.
* Genres like pop, hip-hop, EDM dominate the dataset.
* Valence shows clear emotional trend fluctuations over time.

---

## 🔮 **Future Enhancements**

* Add **Streamlit dashboard** for interactive exploration
* Introduce **ML models** for track popularity prediction
* Add clustering for **genre segmentation**
* Create time-series forecasting for **popularity trends**
* Build a **Spotify API integration** for real-time data

---

## 🤝 **Contributing**

Contributions are welcomed!

1. Fork the project
2. Create a feature branch
3. Commit your changes
4. Open a pull request

---

## 🛡️ **License**

This project is licensed under the **MIT License**.

---

## ⭐ **Support the Project**

If you like this project, consider giving it a **🌟 star** on GitHub!
It helps improve visibility and motivates further development.

```

