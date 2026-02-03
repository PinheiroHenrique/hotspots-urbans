# Urban Hotspot Detection with Geoprocessing and Python

This project presents an **applied spatial analysis pipeline** focused on identifying **urban hotspots** from georeferenced occurrence data using **Python, GeoPandas, and DBSCAN**.

The goal is to demonstrate, in a practical and reproducible way, how **density-based spatial clustering techniques** can support territorial diagnostics, urban planning, and risk analysis.

---

## Concept

- Conversion of tabular data (CSV) into vector data
- Cartographic reprojection to a metric coordinate system
- Application of the **DBSCAN** algorithm for spatial cluster detection
- Generation of an **interactive map** for hotspot visualization
- Persistence of results in a geospatial format (GeoPackage)

---

## 🗂 Project Structure

```text
geo-hotspots-urbanos/
│
├── data/
│   ├── raw/                 # Raw data (CSV)
│   └── processed/           # Processed data (GPKG)
│
├── scripts/
│   └── hotspots.py          # Main processing pipeline
│
├── outputs/
│   └── maps/
│       └── hotspots.html    # Generated interactive map
│
├── requirements.txt
├── README.md
└── .gitignore

