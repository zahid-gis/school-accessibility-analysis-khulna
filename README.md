# 🏫 School Accessibility Analysis in Khulna District, Bangladesh


## 📌 Project Overview

This project presents a GIS-based School Accessibility Analysis for Khulna District, Bangladesh, using QGIS and OpenStreetMap (OSM) data. The analysis evaluates spatial accessibility to schools by creating a 500-meter buffer around educational facilities and assessing road network coverage within accessible areas.

The project demonstrates practical GIS workflows including spatial data preparation, vector geoprocessing, accessibility analysis, cartographic design, and spatial statistics.

---

## 🎯 Objectives

- Analyze the spatial distribution of schools in Khulna District.
- Evaluate school accessibility using a 500-meter buffer.
- Calculate school service coverage area.
- Measure road network length within accessible zones.
- Identify underserved areas for future educational planning.

---

## 🛠 Software Used

- QGIS 3.x
- OpenStreetMap (OSM)
- Geofabrik Bangladesh Extract

---

## 📂 Data Sources

- OpenStreetMap (OSM)
- Geofabrik Open Data
- Khulna District Administrative Boundary

---

## 🗂 Project Workflow

1. Download OSM data from Geofabrik
2. Load administrative boundaries, roads, and POIs into QGIS
3. Extract Khulna District boundary
4. Extract school locations
5. Clip schools to the study area
6. Create a 500-meter buffer around schools
7. Dissolve overlapping buffers
8. Clip road network using the dissolved buffer
9. Calculate road length and coverage area
10. Design the final cartographic map

---

## 🛠 GIS Techniques Used

- Attribute Query
- Feature Extraction
- Clip
- Buffer Analysis
- Dissolve
- Field Calculator
- Spatial Statistics
- Cartographic Design
- Layout Design

---

## 📊 Project Results

| Indicator | Value |
|------------|-------|
| Study Area | Khulna District |
| Total Schools | 960 |
| Buffer Distance | 500 meters |
| School Coverage Area | 529.90 km² |
| District Area | 4648.74 km² |
| Accessibility Coverage | 11.40% |
| Accessible Road Length | 2030.16 km |
| Coordinate System | EPSG:32646 |

---

## 📁 Project Structure

```
school-accessibility-analysis-khulna/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── documentation/
│
├── maps/
│
├── outputs/
│
├── qgis_project/
│
├── screenshots/
│
└── README.md
```

---

## 🗺 Final Map

The final map includes:

- Khulna District Boundary
- School Locations
- 500-meter School Accessibility Buffer
- Accessible Road Network
- Legend
- North Arrow
- Scale Bar
- Locator Map

---

## 💡 Key Skills Demonstrated

- GIS Data Preparation
- Spatial Analysis
- Accessibility Analysis
- Vector Geoprocessing
- Cartographic Visualization
- Spatial Statistics
- OpenStreetMap Data Processing
- QGIS Workflow

---

## 📷 Final Project

### Final Accessibility Map

![Final Map](https://github.com/zahid-gis/school-accessibility-analysis-khulna/blob/main/output/school_accessibility_in_khulna.png))

---

## 🚀 Future Improvements

- Network-based service area analysis
- Population accessibility assessment
- Ward-level accessibility statistics
- Web GIS visualization

---

## 👤 Author

**Zahid Hasan**

GIS Portfolio Project

---

## 📜 License

This project is available under the MIT License.

---

⭐ If you found this project helpful, feel free to star this repository.
