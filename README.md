# IBM Data Science Professional Certificate_Final_Capstone_Project
Capstone Project for IBM Data Science Professional Certificate on Coursera


# Capstone Project – The Battle of the Neighborhoods

This project is part of the **IBM Data Science Professional Certificate** capstone.  
It explores how data science can be applied to **analyze neighborhoods** in a city and help answer practical questions (e.g., where to open a business, which areas are similar, etc.).

---

## Project Overview
The goal of this project is to:
- Use **location data** (Foursquare API) to analyze neighborhoods.
- Explore venue categories and frequencies across neighborhoods.
- Cluster neighborhoods based on similarity.
- Provide actionable insights for decision-making (e.g., selecting the best location for a new restaurant or business).

---

## Repository Contents
- `Capstone_The-Battle-of-the-Neighborhoods.ipynb` → Jupyter Notebook with full project code, analysis, and visualizations.
- `data/` (if applicable) → Contains cleaned datasets or CSVs used in the project.
- `README.md` → This project description.
- (optional) `requirements.txt` → List of dependencies (see below).

---

## Tools & Libraries
- **Python** (3.7+)
- **Libraries**: 
  - `pandas`, `numpy` → data manipulation  
  - `matplotlib`, `seaborn` → visualization  
  - `scikit-learn` → clustering (KMeans)  
  - `geopy`, `folium` → geospatial analysis and interactive maps  
  - `requests`, `json` → API calls  
- **APIs**:
  - [Foursquare Places API](https://developer.foursquare.com/) for venue data

---

## Methodology
1. **Data Collection**: Gather neighborhood and venue data (via APIs).  
2. **Data Cleaning**: Prepare and structure datasets.  
3. **Feature Engineering**: Extract venue categories and frequencies.  
4. **Clustering**: Use **KMeans** to group similar neighborhoods.  
5. **Visualization**: Map and plot clusters for insights.  
