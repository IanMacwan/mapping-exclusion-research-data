# 🗺️ Mapping Exclusion: Immigrant Families and Child Care Inequality in the GTA

**Authors:**  
- Ian Macwan  
- Rayan Roshan  

**Institution:**  
Department of Computer Science, Toronto Metropolitan University  
**Date:** May 9, 2025

---

## 🎯 Purpose of the Report

This report explores **geographic inequalities** in child care access across the Greater Toronto Area (GTA), particularly for **immigrant families**. We examine how **spatial exclusion**—caused by poor walkability, transit accessibility, and infrastructure—limits immigrant communities from accessing affordable, quality child care services.

---

## 🏆 Context & Motivation

While affordability has been addressed in many studies, **location and infrastructure-based access** remain under-examined. This research fills that gap by:

- Analyzing spatial data to identify underserved immigrant communities.
- Highlighting how urban design and transit inequities contribute to systemic exclusion.
- Providing policy recommendations for inclusive child care planning.

---

## 🛠️ Tech Stack

This project leverages a range of open-source tools and libraries for data processing and geospatial visualization:

| Tool/Library   | Purpose                                      |
|----------------|----------------------------------------------|
| `Python`       | Data analysis and processing                 |
| `Pandas`       | Tabular data manipulation                    |
| `Matplotlib`   | Data visualization (bar charts, pie charts)  |
| `Seaborn`      | Statistical plots and visualizations         |

---

## 📊 Data Sources

We used a combination of **government census**, **open municipal data**, and **spatial access datasets**:

- 📍 *2021 Census Data* — [Statistics Canada](https://www12.statcan.gc.ca/census-recensement/2021/)
- 🧭 *Spatial Access Measures* — [StatCan](https://www150.statcan.gc.ca/)
- 🏫 *Licensed Child Care Centres* — [City of Toronto](https://open.toronto.ca/dataset/licensed-child-care-centres/)
- 📌 *Child Care Locations* — [Markham](https://data-markham.opendata.arcgis.com/), [Peel](https://data.peelregion.ca/), [Durham](https://opendata.durham.ca/)
- 🗺️ *Census Subdivision Boundary Files* — [Government of Canada](https://www12.statcan.gc.ca/)

---

## 📈 Key Insights

- **Immigrant-dense suburbs** like Brampton and Mississauga have high populations but **low walkability and transit access** to child care.
- **Toronto** has the highest number of child care centres and accessibility, but surrounding areas lack infrastructure despite demand.
- Suburban areas such as **Caledon** are critically underserved due to **car-dependent planning** and inadequate transit.

---

## 📂 Repository Structure

```
📁 /data                → Cleaned datasets and census data
📁 /code-visulization   → Generated charts and code (Figures 1–8)
📁 /child-care-data     → Datasets with licenced child care centres
📁 /boundaries-data     → Census subdivision boundary files
📄 report.pdf           → Full written report (To be added)
📄 README.md            → This file
```

---

## 📢 Recommendations

1. Expand child care in **high-density immigrant neighbourhoods**.
2. Integrate **transit, zoning, and housing policies** with service planning.
3. Increase **public outreach** to inform immigrant families of available resources.

---

> “Child care is not just a social good—it’s spatial equity.”  

---