
# 🚦 Traffic Accident Pattern Analyzer  
This repository contains the implementation for **Prodigy Infotech Internship Task 5** — analyzing traffic accident data to identify patterns related to road conditions, weather, and time of day, and visualizing accident hotspots and contributing factors.

---

## 🚀 Project Overview  
What’s included:

✅ Data loading and preprocessing (cleaning nulls, standardizing formats)  
✅ Feature engineering: Extracting time, weather, and road condition features  
✅ Exploratory data analysis (EDA) to identify key trends  
✅ Visualization of accident hotspots on maps  
✅ Correlation analysis of contributing factors  
✅ Time-based trend analysis (e.g., accidents by hour/day)

---

## 📁 Files  
- `Prodigy_Infotech_Task_5.ipynb`: Jupyter notebook with full code and insights  
- `traffic_accident_data.csv`: Dataset containing accident logs and features 
---

## 🛠️ Main Workflow  

### 1. Load Dataset  
Load and inspect raw accident data including location, time, and environmental details.

### 2. Preprocess Data  
Handle missing values, format timestamps, normalize categorical data.

### 3. Feature Extraction  
Extract time-of-day, weather types, road conditions, etc.

### 4. Analyze Patterns  
Study accident frequency by:  
- Hour of the day / Day of the week  
- Weather conditions (e.g., rain, fog)  
- Road types and surface conditions

### 5. Visualize Hotspots  
Plot geospatial heatmaps using `folium` or `plotly` to visualize accident-dense regions.

### 6. Correlation Study  
Find statistical relationships between variables contributing to accidents.

---

## 📊 Final Results  
- 🌧️ Accidents peak during rain and foggy conditions  
- 🕐 Most accidents happen between 5–8 PM (evening rush hour)  
- 🗺️ Hotspots located near intersections and poorly lit roads  
- ✅ Data-backed identification of top 5 contributing factors

---

## ✨ Future Work  
- Integrate real-time traffic API data for dynamic analysis  
- Predict accident risk levels using classification models  
- Recommend preventive measures based on identified patterns  
- Develop an interactive dashboard (e.g., Streamlit / Dash)

---

## 👨‍💻 Author  
Made by **Shantanu Mali**  
Feel free to connect! 🚀
