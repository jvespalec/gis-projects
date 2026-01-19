# Cartography Projects (GEOG 370: Intro to Cartography)

The above projects were completed as part of an Intro to Cartography course, GEOG 370. Each project highlights different aspects of cartographic design, GIS, and data visualization. The projects were created using ArcGIS Pro, Adobe Illustrator, and various online tools such as Projection Wizard and Mapshaper.

---

## Lab 1: Vermont Maple Syrup Farms
This was my first design project using ArcGIS Pro. I built foundational skills with geospatial datasets, adjusting map projections using Projection Wizard, and cartographic generalization using Mapshaper.  

**Challenges:**  
- Ensuring text was legible around lines and polygons (e.g., lake and river labels)  
- Adjusting callouts consistently across the page to ensure a balanced visual hierarchy  

---

## Lab 2: Political Map of Africa: Visualizing European Colonization
The purpose of this map was to show a high level of detail in a small space while maintaining a clean, consistent appearance. I gained more experience in Illustrator, such as using Type on a Path, Lasso, Curvature, and Group Selection tools.  

**Challenges:**  
- Some labels were too far away from the city's location, so it was unclear which feature it belonged to
- Some labels were oo close together, so it looked cluttered or was overlapping other features
- I had to place labels on top of lines, so letters became difficult to read. I used a halo around the text to improve legibility.

---

## Lab 3: Dairy Cow Density in Wisconsin
This project was a choropleth map illustrating the density of dairy cows in Wisconsin counties.  

**Techniques used in ArcGIS Pro:**  
- Data classification  
- Normalization (cows per unit area)  
- Symbology adjustment (choropleth shading)  
- Legend design  

---

## Final Project: The Lasting Effects of Historic Redlining in Milwaukee County
This self-driven project combined all the material covered in the course: cartographic design principles, generalization, map projections, data collection and analysis, ArcGIS Pro, and Adobe Illustrator.  

**Goals:**  
1. Illustrate the relationships between historical redlining boundaries in Milwaukee County and present-day school quality  
2. Visualize how proximity to highly rated schools intersects with historically disadvantaged neighborhoods  

**Data & Methods:**  
- 1938 Home Owners’ Loan Corporation (HOLC) redlining map of Milwaukee  
- Statewide school report card data from the Wisconsin Department of Public Instruction  
- Data cleaning and categorization in Microsoft Excel to create school quality groups using five different levels 
- ArcGIS Pro used for:  
  - Choropleth mapping of redlining zones (A–D)  
  - Symbolization of schools by quality category  
  - Buffer analysis around highly rated schools  
  - Heat map to highlight accessibility patterns  
- Adobe Illustrator used for final map design

**Maps Produced:**  
- Choropleth map of original HOLC redlining boundaries with school quality data by district  
- Heat map illustrating the degree of accessibility to highly rated schools in relation to formerly redlined areas  
---

##

# General GIS Projects (GEOG 377: Intro to GIS) 

The following works were a result of a 6-week "project" as part of the lab portion of GEOG 377, Intro to GIS, focusing on identifying suitable sites for a hypothetical laboratory and office building. Using a provided land use map and corresponding spatial data, we evaluated site suitability through both vector and raster spatial analysis, incorporating various environmental and logistical constraints.


**GIS Processes Used:**

Spatial database compilation
- Integrated different data formats (JPEG, DWG, SHP, KML, JSON) into a single file geodatabase
- Merged all datasets into a common projected coordinate system, WGS 1984 UTM Zone 18N

Georeferencing and digitization
- Georeferenced a scanned land use map using control points and RMSE evaluation
- Digitized land use boundaries and constructed polygons

Vector-based suitability analysis
- Applied buffer constraints
- Used attribute queries and overlay operations to identify suitable polygons
- Produced potential candidate sites with clear and defined boundaries

Vector-to-raster conversion
- Converted vector layers into raster datasets
- Selected an appropriate cell size based on analysis scale and constraints

Raster distance analysis
- Generated Euclidean distance rasters for sewer lines and streams
- Applied distance thresholds using maximum distance parameters

Raster overlay and map algebra
- Combined multiple suitability rasters using Cell Statistics such as mean, minimum, and maximum
- Evaluated how different overlay operators affect site selection outcomes
- Interpreted NoData handling and its implications for spatial analysis
