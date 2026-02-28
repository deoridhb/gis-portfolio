# gis-portfolio
QGIS projects demonstrating raster, vector, and spatial analysis
World Map of GIS Software and Their Origin Countries (QGIS)

Objective
Visualize major GIS software and their countries of origin on a world map.

Method

# World administrative boundary shapefile

CSV data (software name, origin country, latitude–longitude)

Rule-based labeling and point symbology in QGIS

Output
<img width="1378" height="974" alt="image" src="https://github.com/user-attachments/assets/73482713-c318-4ac9-aad2-0565057f128e" />

World map showing global distribution of GIS software

Skills
CSV to spatial layer, labeling, map layout design (QGIS)

# India Map with State Capitals and Temperature (QGIS)

Objective
Create a thematic map of India displaying state capitals and their average temperature.

Method

India state boundary shapefile

CSV data (capital, latitude–longitude, temperature)

Attribute-based labeling and color ramp symbology

Output
<img width="1378" height="976" alt="image" src="https://github.com/user-attachments/assets/fbf9adbd-6860-4bb5-886e-f841820e49c6" />

India map showing spatial variation of temperature across capitals

Skills
Thematic mapping, CSV import, symbology & cartographic layout (QGIS)

# Georeferencing & Digitization of Area of Interest (QGIS)

Objective
Georeference a Survey of India toposheet and digitize features within the area of interest.

Method

Georeferenced scanned toposheet using Polynomial 2 transformation and control points

Created point, line, and polygon shapefiles

Digitized features using QGIS editing tools

Output

Georeferenced raster and digitized vector layers

Skills
Georeferencing, digitization, spatial accuracy handling (QGIS)

# NDVI Analysis using Landsat 8–9

Objective
Calculate and visualize vegetation health using NDVI for a selected study area.

Data & Method

Landsat 8–9 multispectral imagery (USGS EarthExplorer)

NDVI calculated using Raster Calculator:
NDVI = (NIR − Red) / (NIR + Red)

Applied single-band pseudocolor symbology for interpretation

Tools
ArcGIS 10.8, Raster Calculator, Multiband rendering

Output
<img width="1883" height="994" alt="image" src="https://github.com/user-attachments/assets/e4a2ba5e-08ab-4d0a-9b32-ad24835d5a07" />

NDVI map showing vegetation health and density

Key Insights

Higher NDVI values indicate healthy vegetation

Lower or negative values represent water or non-vegetated areas

Skills
Satellite image processing, spectral index calculation, thematic visualization

# Network Analysis: Route, Closest Facility & Service Area

Objective
Perform network analysis on a road network to identify the shortest route, closest facility, and service areas.

Method

Prepared road network dataset and clipped it to the study area

Built a network dataset and defined impedance

Solved shortest route between locations

Identified closest facility to incidents

Generated service areas based on travel distance/time

Tested route behavior using polygon barriers

Tools
ArcGIS 10.8, Network Analyst Extension

Output
<img width="1883" height="997" alt="image" src="https://github.com/user-attachments/assets/fe78502d-5c15-4180-b33f-cfd31c9dd80c" />

Shortest route map

Closest facility routes

Service area polygons

Skills

# Network dataset creation, route optimization, service area analysis, spatial decision support Georeferencing & Digitization of Area of Interest (QGIS)

Objective
Georeference a Survey of India toposheet and digitize features within the area of interest.

Method

Georeferenced scanned toposheet using Polynomial 2 transformation and ground control points

Generated georeferenced raster in WGS 84

Created point, line, and polygon shapefiles

Digitized features using QGIS editing tools

Tools
QGIS 3.28, Georeferencer, Digitizing tools

Output
<img width="940" height="502" alt="image" src="https://github.com/user-attachments/assets/004ce6c1-f837-40d2-b5b2-306caf3a7a3e" />

Georeferenced toposheet
<img width="963" height="498" alt="image" src="https://github.com/user-attachments/assets/7c7d7630-021f-4a31-b5e7-bd640d7b0aa5" />
<img width="940" height="498" alt="image" src="https://github.com/user-attachments/assets/9b52e27e-b645-4a75-8395-440c8a1f8341" />

Digitized vector layers for spatial analysis

Skills
Georeferencing, control point selection, raster-to-vector digitization, spatial accuracy handling

# DEM Terrain & Hydrological Analysis (QGIS)

Objective
Analyze terrain characteristics and drainage patterns using Digital Elevation Model (DEM) data.

Data & Method

SRTM DEM (USGS EarthExplorer)

Generated hillshade, slope, aspect, and ruggedness index

Reprojected DEM and applied sink filling

Derived flow direction, watershed basins, and drainage routes

Tools
QGIS 3.28, Terrain Analysis, SAGA Hydrology tools

Output
<img width="1883" height="1001" alt="image" src="https://github.com/user-attachments/assets/a1198350-dc61-42dd-a5b8-c24dc9f0ebf1" />
<img width="1883" height="1006" alt="image" src="https://github.com/user-attachments/assets/855d7f2d-6f11-4a6a-b1d8-ea44a4a07b79" />

Terrain derivative maps (slope, aspect, hillshade, ruggedness)
<img width="1883" height="997" alt="image" src="https://github.com/user-attachments/assets/4110f52e-0960-40c4-b60b-515926f40c4b" />

Watershed basins and flow direction layers

Skills
DEM processing, terrain analysis, hydrological modeling, raster visualization

# Flood Susceptibility Mapping using GIS–AHP (Google Earth Engine)

Objective
Develop a flood susceptibility map to identify flood-prone areas using GIS-based AHP and cloud-based geospatial analysis.

Study Area
Kamrup Metropolitan District, Assam, India

Data & Method

Multi-source geospatial datasets processed in Google Earth Engine (GEE)

Flood conditioning factors:
Elevation, slope, aspect, SPI, TWI, flow accumulation, land cover, rainfall, STI

Weights assigned using Analytical Hierarchy Process (AHP)

Consistency Ratio (CR) = 0.03 (acceptable)

Weighted overlay used to generate final flood susceptibility map

Tools
Google Earth Engine, GIS, AHP

Output

<img width="1378" height="974" alt="image" src="https://github.com/user-attachments/assets/2154cd1e-e51d-4b37-a269-7321be20f6f7" />

Flood susceptibility zones (Low–Very High)

<img width="1235" height="873" alt="image" src="https://github.com/user-attachments/assets/3d8180ee-8954-4834-bc89-21956106b7ae" />

<img width="1164" height="763" alt="image" src="https://github.com/user-attachments/assets/abdc0a46-e41f-4ccf-9998-234bbf569f04" />

<img width="1215" height="859" alt="image" src="https://github.com/user-attachments/assets/f8fa5ad4-554e-44e2-ac23-999245e09633" />

<img width="1125" height="796" alt="image" src="https://github.com/user-attachments/assets/33bfd935-8f65-4dce-99f7-402a704b822f" />

<img width="1263" height="893" alt="image" src="https://github.com/user-attachments/assets/1969fa2e-2de5-45d3-ad38-b1731c07f866" />

Supporting thematic layers (SPI, TWI, slope, rainfall, LULC)

Key Findings

Hydrological and topographic factors strongly influence flood occurrence

High-susceptibility zones align with low-lying and high-flow accumulation areas

Results support flood risk management and urban planning

Skills
Flood modeling, multi-criteria decision analysis (AHP), Google Earth Engine, GIS-based hazard mapping

# River Bank Erosion & Accretion Analysis – Brahmaputra River (RS & GIS)

Objective
Analyze erosion and accretion dynamics along the Brahmaputra River in Kamrup and Nalbari districts, Assam using remote sensing and GIS.

Data & Method

Sentinel-2 LULC data (2017 & 2022, 10 m resolution)

LULC reclassification and change detection

Raster-to-polygon conversion for erosion/accretion zones

River channel and centerline extraction

Area calculation to quantify erosion and accretion

Tools
ArcGIS 10.8, Raster Calculator, Reclassification, Overlay & Conversion tools

Key Results

<img width="794" height="1123" alt="image" src="https://github.com/user-attachments/assets/bcd8059f-d7c1-44e4-a01c-cf02020f3cc7" />

<img width="794" height="1123" alt="image" src="https://github.com/user-attachments/assets/59576a2f-484b-4eb2-a9d2-085d7a0b27a2" />

<img width="794" height="1123" alt="image" src="https://github.com/user-attachments/assets/3615a494-3d27-4b7a-9e1b-161c74ede102" />

<img width="571" height="344" alt="image" src="https://github.com/user-attachments/assets/882f7097-c801-44c0-8827-1c1b2826d3e5" />

Erosion: 64.94 km²

Accretion: 71.11 km²

Significant loss of vegetation and rangeland

Increase in water bodies and built-up areas

Confirms highly dynamic nature of the Brahmaputra river channel

Skills
LULC change detection, river morphology analysis, erosion–accretion mapping, GIS-based spatial analysis
