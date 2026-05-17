# GIS Portfolio – Rayce Perales
GIS Portfolio displaying knowledge, skill, capabilities and accomplishments; created by Rayce Perales.

---

## Project 1 – Building Footprint Digitization (Snug Harbor, NC)

**Tools:**  
ArcGIS Pro 3.6.4  

**Skills:**  
Digitizing, editing workflows, cartographic layout, metadata, coordinate systems  

![Building Footprints – Snug Harbor, NC](building_footprint_digitalization_snugharbor_layout.jpg)

**Overview:**  
This project demonstrates manual digitization of building footprints using high‑resolution Esri World Imagery. I selected a neighborhood in Snug Harbor, NC and created a new polygon feature class to capture all visible structures. Approximately 50 building footprints were digitized with clean geometry and attribute fields.

**Workflow:**

- Created a new file geodatabase and building footprint feature class  
- Set the coordinate system to NAD 1983 StatePlane North Carolina FIPS 3200 (US Feet)  
- Digitized each structure using polygon editing tools  
- Applied consistent symbology for clarity  
- Designed a professional map layout with legend, scale bar, north arrow, and metadata  
- Exported final outputs as Web JPEG (for display) and Vector PDF (for download)

**Download full map (PDF):**  
[Building Footprints – Snug Harbor, NC (Vector PDF)](building_footprint_digitalization_snugharbor.pdf)

---

## Project 2 – Road Topology Correction (Snug Harbor, NC)

**Tools:**  
ArcGIS Pro 3.6.4  

**Skills:**  
Topology validation, error correction, editing workflows, cartographic layout, geodatabase management  

![Road Topology Correction – Snug Harbor, NC](road_topology_snugharbor.jpg)

**Overview:**  
This project demonstrates the identification and correction of topology errors within a road centerline dataset. The left map displays the original network containing dangles, pseudonodes, and improper intersections. The right map shows the corrected and validated topology after resolving invalid geometries and marking legitimate intersections as exceptions.

**Workflow:**

- Created a new file geodatabase and imported the road centerline dataset  
- Applied topology rules to identify dangles, pseudonodes, and improper intersections  
- Corrected invalid geometries using snapping, vertex editing, and feature modification tools  
- Marked legitimate intersections as exceptions to maintain accurate connectivity  
- Designed a dual‑map layout comparing original vs. corrected topology  
- Exported final outputs as Web JPEG (for display) and Vector PDF (for download)

**Download full map (PDF):**  
[Road Topology Correction – Snug Harbor, NC (Vector PDF)](road_topology_snugharbor.pdf)

---

## Project 3 – LiDAR‑Derived Terrain Visualization (Snug Harbor, NC)

**Tools:**  
ArcGIS Pro 3.6.4  

**Skills:**  
LiDAR processing, DEM generation, hillshade creation, contour extraction, raster analysis, cartographic layout  

![LiDAR‑Derived Terrain Visualization – Snug Harbor, NC](lidar_terrain_model_snugharbor.jpg)

**Overview:**  
This project uses 2019 North Carolina LiDAR data to generate a bare‑earth Digital Elevation Model (DEM), hillshade, and 2‑foot elevation contours for Snug Harbor, NC. The final map visualizes terrain variation in a coastal residential area using LiDAR‑derived elevation products.

**Workflow:**

- Downloaded 2019 LiDAR tiles from the NC Spatial Data Download (NC SDD) portal  
- Created a LAS Dataset and applied ground‑only classification filters  
- Generated a bare‑earth DEM using LAS Dataset to Raster  
- Created a hillshade using Spatial Analyst tools  
- Extracted 2‑foot contours and styled index contours for clarity  
- Designed a clean terrain visualization layout with title, scale bar, north arrow, and metadata  
- Exported final outputs as Web JPEG (for display) and Vector PDF (for download)

**Download full map (PDF):**  
[LiDAR‑Derived Terrain Visualization – Snug Harbor, NC (Vector PDF)](lidar_terrain_model_snugharbor.pdf)

## Project 4 – School Safety Buffer & Population Impact Analysis (Perquimans County, NC)

**Tools:**  
ArcGIS Pro 3.6.4  

**Skills:**  
Buffer analysis, spatial joins, select-by-location workflows, census data integration, population estimation, cartographic layout, geoprocessing workflow design  

![School Safety Buffer & Population Impact Analysis – Perquimans County, NC](school_safety_analysis_perquimans.jpg)

**Overview:**  
This project evaluates development and population exposure within 1,000 feet of public schools in Perquimans County, NC. Using school locations, building footprints, and census block population data, I identified structures and residents located inside the school safety zone. The analysis demonstrates real-world GIS skills used in planning, emergency management, and public safety assessments.

**Workflow:**

- Downloaded public school locations from NC OneMap and clipped to Perquimans County  
- Downloaded countywide building footprints from the NC Spatial Data Download (NC SDD) portal  
- Downloaded census blocks with population attributes from NC OneMap  
- Created a 1,000‑foot dissolved buffer around all public schools  
- Selected and exported all buildings intersecting the buffer  
- Selected intersecting census blocks and summarized total population  
- Designed a professional map layout showing schools, buffer, impacted buildings, and contextual layers  
- Exported final outputs as Web JPEG (for display) and Vector PDF (for download)

**Outcome:**  
The analysis identified **261 buildings** located within 1,000 feet of public schools. Census block population data indicates approximately **1,186 residents** live inside the school safety buffer. These results provide a clear understanding of development and population exposure surrounding local schools, supporting planning, emergency management, and policy evaluation efforts.

**Download full map (PDF):**  
[School Safety Buffer & Population Impact Analysis – Perquimans County, NC (Vector PDF)](school_safety_analysis_perquimans.pdf)
