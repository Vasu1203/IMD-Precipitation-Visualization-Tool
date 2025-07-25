# 🌧️ IMD Precipitation Analysis of Past Data (2020–2024)

This project focuses on analyzing high-resolution gridded daily precipitation data over **Chhattisgarh** using datasets from the  
**Indian Meteorological Department (IMD)**. The data is in NetCDF format with a resolution of **0.25° × 0.25°** and spans the years **2020 to 2024**.

It includes:

- 🌍 Spatial rainfall visualizations using **Folium**  
- 📊 Computation and visualization of **Standardized Precipitation Index (SPI)** for drought assessment  
- 🧪 Monthly and annual analysis of precipitation trends  
- 📌 Many more insightful visualizations and analytics

---

## 📁 Dataset Source

The gridded rainfall data was obtained from the official IMD portal:  
🔗 [IMD Gridded Rainfall Data (0.25° x 0.25°)](https://imdpune.gov.in/cmpg/Griddata/Rainfall_25_NetCDF.html)

- **Format:** NetCDF (`.nc`)  
- **Coverage:** Daily rainfall data across India  
- **Resolution:** 0.25° × 0.25°  
- **Period:** 2020 to 2024 (subset extracted for Chhattisgarh)

---

## 🧰 Key Features

### ✅ Data Preprocessing

- Merged and subsetted `.nc` files to extract rainfall data specific to **Chhattisgarh**  
- Aggregated daily rainfall data to compute **monthly totals**

### ✅ Rainfall Visualization

- Created **interactive Folium-based maps** for every month from **2020 to 2024**  
- Used **color-coded polygons** to depict rainfall intensity  
- Applied **GeoJSON clipping** to focus exclusively on the **Chhattisgarh** region

### ✅ SPI Calculation

- Computed **Standardized Precipitation Index (SPI)** using both **Gamma** and **Normal** distributions  
- Visualized SPI maps interactively to highlight **meteorological drought severity**

---

## 📌 Additional Highlights

- Interactive `.html` maps viewable in-browser without setup  
- Structured, modular code for easy extension  
- Clean folder and file management for clarity and reuse

---

## 🧪 Technologies Used

- Python, xarray, netCDF4, pandas, numpy  
- geopandas, folium, shapely, branca  
- matplotlib, seaborn, scipy

---

## 🙌 Acknowledgements

- **Data Source:** Indian Meteorological Department ([IMD Pune](https://imdpune.gov.in))  
- This project is intended for academic and research purposes only.

---
