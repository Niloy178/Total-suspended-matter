# 🌊 Total Suspended Matter Analysis of Kaptai Lake (2024)

This project analyzes **Total Suspended Matter (TSM)** in **Kaptai Lake** for the year 2024 using geospatial Python tools and Google Earth Engine satellite data.

I calculated the **monthly mean Total Suspended Matter** and generated spatial visualizations to understand seasonal variation patterns across the lake.

The complete workflow is available in the uploaded Jupyter Notebook.

---

## 📍 Study Area

**Kaptai Lake**, Bangladesh
The largest artificial lake in Bangladesh, located in Rangamati District.

---

## 🛰️ Data Source

* **Dataset:** `COPERNICUS/S2_SR_HARMONIZED`
* **Platform:** Google Earth Engine
* **Satellite:** Sentinel-2 Surface Reflectance
* **Year:** 2024
* **Temporal Resolution:** Monthly Mean Aggregation

---

## 🧮 Methodology Overview

Here’s what was done step by step:

1. Defined Kaptai Lake boundary.
2. Filtered Sentinel-2 SR imagery for 2024.
3. Applied cloud masking.
4. Calculated Total Suspended Matter (TSM) using spectral band relationships.
5. Aggregated monthly mean TSM.
6. Visualized spatial distribution of TSM.
7. Exported processed data for analysis.

---

## 🛠️ Technologies & Libraries Used

* **Google Earth Engine (GEE)**
* **geemap**
* **pandas**
* **geopandas**
* **xarray**
* **matplotlib**
* **Jupyter Notebook**

---

## 📊 Output

* Monthly mean TSM values for 2024
* Spatial visualization maps
* Time-series trend representation
* Processed geospatial data analysis

---

## 📈 Sample Visualization

(Generated using matplotlib and geemap inside the notebook)

You can explore:

* Monthly variation patterns
* Spatial concentration differences
* Seasonal trends

---

## 📂 Repository Structure

```
├── Total_Suspended_Matter_Kaptai_2024.ipynb
├── README.md
```

---

## 🚀 How to Run

1. Clone the repository
2. Install required dependencies
3. Authenticate Google Earth Engine
4. Open the Jupyter Notebook
5. Run cells sequentially

---


## 👤 Author

Nuruzzaman Islam
