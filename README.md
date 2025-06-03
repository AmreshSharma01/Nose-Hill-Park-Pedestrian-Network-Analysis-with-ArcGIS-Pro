# Nose Hill Park Pedestrian Network Analysis with ArcGIS Pro

## Project Overview

This project was developed as part of ENGO 641 (Design and Implementation of Geospatial Information Systems) at the University of Calgary. The objective was to create a pedestrian network dataset for Nose Hill Park (NW Calgary), build a network dataset using ArcGIS Pro, and perform shortest-path network analysis between multiple user-selected locations.

This project demonstrates geodatabase design, network dataset building, route optimization, spatial analysis, and professional map layout creation.

## Technologies Used

- ArcGIS Pro (Network Analyst Extension)
- File Geodatabase (.gdb)
- NAD 1983 3TM 114 coordinate system
- Digitized Feature Classes
- Network Dataset creation
- Shortest Path Network Analysis
- Map Layout Design & Visualization

## Project Structure

- `Ujjal_Issac_Amresh.aprx` — ArcGIS Pro Project File
- `Ujjal_Issac_Amresh.gdb/` — File Geodatabase with paths and network dataset
- `GpMessages/`, `ImportLog/`, `.backups/` — ArcGIS system logs
- `Ujjal_Issac_Amresh.atbx` — ArcGIS Toolbox File
- `Assignment 5-b ENGO 641.pdf` — Project report with detailed analysis and map layouts
- PNG image files for map layouts and route visualizations

## Project Workflow

### 1️⃣ Coordinate System Setup

- NAD 1983 3TM 114 (Central meridian 114°, Datum NAD83)

### 2️⃣ Digitization & Editing

- Digitized pedestrian pathways in Nose Hill Park using ArcGIS Pro editor tools.
- Shared vertices were applied to ensure topological correctness.

### 3️⃣ Network Dataset Creation

- Built network dataset (`pathsND`) for performing shortest-path routing.

### 4️⃣ Network Analysis

- Conducted shortest route analysis between multiple pairs of points.
- Calculated route lengths and visualized routing results.

### 5️⃣ Map Layout Design

- Created multiple layouts visualizing network edges, junctions, and routes.

## Visualization

### Step 1 (Project Setup)
![Step 1](step%201.png)

### Nose Hill Park Extent
![Nose Hill Park](Nose%20Hill%20Park.png)

### Full Network Layout
![Map Layout](map%20layout.png)

### Shortest Routes

**Route 1:**  
![Route 1](route%201.png)

**Route 2:**  
![Route 2](route%202.png)

**Route 3:**  
![Route 3](route%203.png)

**All Routes Combined:**  
![All Routes](all%203%20routes.png)

## Project done by:

- Amresh Sharma (30233389)
- Isaac Kwabena Agyapong (30222691)
- Ujjal Baniya (30232571)

## Supervisor

Prof. Emmanuel Stefanakis — Department of Geomatics Engineering, University of Calgary

## License

This repository is for academic demonstration purposes only.
