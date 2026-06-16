# 📊 Digital Fitness Demand Analysis
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-green)
![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-orange)
![Status](https://img.shields.io/badge/Project-Complete-brightgreen)

## Python-Data-Driven-Product-Management-Conducting-a-Market-Analysis

This Quick exploration from local and international markets to find opportunities for your fitness products based on data manipulation skills to examine data about online interest in home gyms, gym workouts, home workouts, and fitness products.

---
## 📑 Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Preparation](#data-preparation)
- [Data Exploration](#data-exploration)
- [Data Analysis](#data-analysis)
- [Findings](#findings)
- [Visual Insights](#visual-insights)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

---
## 📌 Project Overview
This project explores **global demand for fitness-related searches** using Google Trends data.

🎯 **Objective:**  
Help a fitness studio expand its **digital fitness offerings** by analysing:
- Trends over time  
- Impact of COVID-19  
- User preferences (home vs gym workouts)  
- High-potential international markets  

---
## 📂 Data Sources
Datasets used:

- `workout.csv` → Global search interest for *"workout"*  
- `three_keywords.csv` → Trends for:
  - Home workout  
  - Gym workout  
  - Home gym  
- `workout_geo.csv` → Country-level workout interest  
- `three_keywords_geo.csv` → Country-level keyword comparison  

📌 Source: Google Trends (normalised index from 0 to 100)

---
## 🛠 Tools
- Python 3  
- pandas  
- matplotlib  
- Jupyter Notebook  

---
## ⚙️ Data Preparation
Key steps:
- Converted date columns to `datetime`  
- Ensured numeric types using `pd.to_numeric()`  
- Filtered data for COVID period (2020)  
- Cleaned missing or inconsistent values  

---
## 🔍 Data Exploration
Exploration included:
- Time series visualization of workout trends  
- Keyword comparisons over time  
- Country-level distribution analysis  

---
## 📈 Data Analysis

### Business Questions
1. When did workout searches peak globally?  
2. What keyword was most popular during COVID vs today?  
3. Which country has the highest workout interest?  
4. Which market is best for home workout expansion?  


### Approach

- Used **time-series analysis** to identify peaks  
- Compared **average keyword popularity during 2020 (COVID period)**  
- Extracted **latest available data** for current trends  
- Performed **country-level comparisons** using aggregated indexes  

---
## ✅ Findings

| Insight | Result |
|--------|--------|
| Peak workout interest | **2020** |
| Most popular during COVID | **Home workout** |
| Most popular now | **Gym workout** |
| Top country (US/AUS/JPN) | **United States** |
| Best home workout market | **Philippines** |

### Key Takeaways
- COVID significantly accelerated **digital fitness adoption**  
- Users have partially returned to gyms, but **home fitness remains strong**  
- Southeast Asia shows promising growth for digital fitness 

---
## 🚀 Recommendations
### 📱 Digital Product Strategy
- Expand **home workout** programs
- Develop **on-demand** and **mobile-first** content

### 🌍 Market Expansion
- Prioritise the **Philippines** for virtual fitness rollout
- Test campaigns in similar SEA markets

### 🔄 Hybrid Fitness Model
Combine:
- 🏠 **Digital** (home workouts)
- 🏋️ **Physical** (gym sessions)

### 📊 Continuous Monitoring
- Track Google Trends regularly
- Adapt offerings to shifting user preferences

---
## ⚠️ Limitations
- Google Trends provides **relative, not absolute data**
- Limited keyword selection may miss other trends
- Country-level aggregation hides regional variations
- COVID period simplified to one year (2020)
- No adjustment for seasonality

---
## ⭐ Portfolio Value
This project showcases:
- ✅ Data cleaning & preprocessing
- ✅ Time-series analysis
- ✅ Business-oriented insights
- ✅ Clear and structured data storytelling

---
### 👤 Author
*Axel Chenu*

