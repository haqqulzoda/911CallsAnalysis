# 📊 911 Calls Emergency Analysis (EDA + Mapping)

A real-world exploratory data analysis (EDA) project using 911 emergency call data from Montgomery County, Pennsylvania. This notebook uncovers time-based and spatial patterns in emergency calls, visualizes them using Python libraries, and offers actionable insights for emergency response optimization.

---

## 🔍 Project Overview

- **Dataset**: 911 call records including location, reason, timestamp, and emergency title.
- **Goal**: Understand patterns in emergency calls over time and geography to support decision-making for emergency services.
- **Tech Stack**: Python, Pandas, Matplotlib, Seaborn, Folium

---

## 🚀 Key Features

✅ Clean and process messy real-world timestamped data  
✅ Time-series and categorical feature engineering (Hour, Day, Reason)  
✅ Visualize trends by hour, weekday, month  
✅ Detect peak emergency periods (e.g., business hours, mid-week)  
✅ Heatmap-based spatial visualization using `folium`  
✅ Business-oriented insights and improvement suggestions  
✅ Ready for interview discussions

---

## 🗃️ Dataset Details

- 📁 Source: [Kaggle Link](https://www.kaggle.com/datasets/mchirico/montcoalert))*  
- 🔢 Size: ~50K records  
- 📌 Columns: `lat`, `lng`, `title`, `timeStamp`, `twp`, `zip`, ...

---

## 📈 Exploratory Data Analysis

- 📅 Time-based Features: Hour, Day, Month, Weekday
- 📊 Visualizations:
  - Reason distribution (`EMS`, `Fire`, `Traffic`)
  - Calls by day of week & month
  - Daily trend over time
  - Call volume by hour
  - Interactive emergency location heatmap

---

## 🌍 Geospatial Analysis

- Created an interactive heatmap using `folium` and `HeatMap`
- Shows emergency hotspots centered around key zip codes and townships
- Map automatically centers on median lat/lng for better view

---

## 🧠 Insights & Recommendations

- **Most frequent call reason**: EMS  
- **Peak hours**: 8am – 6pm (business hours)  
- **Busiest days**: Weekdays, especially Wednesday & Friday  
- **High-call areas**: NORRISTOWN, LOWER MERION

💡 **Suggestions**:
- Use clustering to optimize resource allocation by region  
- Build time-series models to predict high-volume periods  
- Create real-time dashboards for emergency monitoring

---

## 🔧 Tech Stack

| Category | Tools Used |
|----------|------------|
| Language | Python |
| Libraries | Pandas, Seaborn, Matplotlib, Folium |
| Notebook | Jupyter |
| Visualization | Static (Seaborn, Matplotlib), Interactive (Folium) |

---

## 🧑‍💼 Why This Project Stands Out

✅ Real-world, messy data  
✅ End-to-end workflow from cleaning to insight  
✅ Shows strong EDA, visualization, and interpretation skills  
✅ Geospatial thinking via heatmaps  
✅ Business thinking: links insights to action

---

## 📚 What I Learned

- Handling and engineering datetime features
- Visualizing time-based patterns effectively
- Spatial plotting with Folium
- How to communicate technical findings for operational use

---

## 💡 Future Work

- 🧠 Predictive modeling of emergency volume
- 📍 Clustering & classification of emergency types by region
- 📊 Streamlit dashboard for public-facing summary

---

## 📂 Project Structure

```bash
911-calls-analysis/
│
├── 911_Calls_EDA.ipynb         # Main Jupyter notebook
├── README.md                   # Project overview
