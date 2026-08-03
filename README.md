# Lahore-City-Explorer-pandas-Folium-
Interactive geospatial exploration and footfall analysis of key places in Lahore using pandas and Folium.
# 🏙️ Lahore City Explorer (pandas + Folium)

An interactive geospatial analysis notebook that visualizes key places across Lahore, Pakistan. Using `pandas` for data manipulation and `Folium` for interactive mapping, this project analyzes visitor footfall, category distributions, and spatial density patterns across the city.

---

## 📌 Features

* **Data Exploration:** Summary statistics including average ratings and total footfall categorized by venue type (Heritage, Shopping, Education, Parks, etc.).
* **Category Color-Coding:** Distinct visual marker colors assigned based on location categories.
* **Proportional Sizing:** Marker radii dynamically scaled relative to daily visitor footfall for instant visual comparison.
* **Interactive Popups:** Rich HTML popups display place name, category, rating, and daily footfall upon clicking a marker.
* **Density Heatmap:** Weighted heatmap overlay visualizing overall footfall density patterns across Lahore.
* **Toggleable Layers:** Organized `FeatureGroup` layers enabling viewers to toggle specific categories on and off.

---

## 📁 Repository Structure

```text
.
├── lahore_places.csv     # Input dataset containing coordinates, footfall, and ratings
├── solution_notebook.ipynb# Main Jupyter Notebook containing complete commented code
├── lahore_map.html       # Standalone exported interactive Folium HTML map
└── README.md             # Project documentation
