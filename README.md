# 🚧 Traffic Accident Data Analysis & Visualization

This project analyzes traffic accident data to uncover patterns related to **road conditions**, **weather**, and **time of day**. It also includes **visualizations of accident hotspots** using geolocation data.

## 🎯 Objective

- Identify key contributing factors to accidents (e.g., weather, road condition, time).
- Visualize accident trends and distributions.
- Generate heatmaps to highlight geographic accident hotspots.

## 🧠 Insights Gained

- 🚗 Most accidents occurred during the **Evening** and **Night**.
- 🌧️ Accidents are more frequent under **rainy** or **foggy** weather.
- 🛣️ **Wet or slippery** roads significantly increase accident likelihood.
- 📍 Accident hotspots are concentrated in urban/high-traffic zones.

## 🛠️ Technologies Used

- **Python**
- `pandas` – data manipulation  
- `seaborn` & `matplotlib` – data visualization  
- `folium` – interactive map visualization  
- `datetime` – time categorization  

## 📊 Key Visualizations

- Count plots of accidents by:
  - Road condition
  - Weather
  - Time of day
- Heatmap of accident locations using `folium`

## 📂 Dataset

- Format: CSV
- Columns: `weather`, `road_condition`, `time`, `latitude`, `longitude`, `severity`, etc.
- Source: Kaggle


