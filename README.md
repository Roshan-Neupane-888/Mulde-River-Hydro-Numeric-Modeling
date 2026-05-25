## Project Background
This project focused on setting up robust, predictive numerical models to simulate river dynamics and assess large-scale flood hazards along the Mulde River catchment. Accurate flood hazard mapping requires understanding how complex hydraulic structures interact with varying flow velocities and water depths during peak discharge events. 

To achieve this, our team integrated geographical information systems (GIS) with both one-dimensional (1D) and two-dimensional (2D) hydrodynamic computational models to map flood extents and evaluate local vulnerabilities.

## My Core Contributions & Role
As a hydraulic modeling specialist on this project, I was responsible for model geometry setup, mesh generation, and hydrodynamic simulation:
* **1D Hydraulic Modeling:** Built and calibrated a 1D HEC-RAS model to evaluate steady and unsteady river flow profiles across defined channel cross-sections.
* **Geospatial Processing & Mesh Generation:** Utilized QGIS to process digital elevation models (DEMs), delineate river catchments, extract geometric attributes, and generate high-quality, unstructured computational meshes required for 2D calculations.
* **2D Hydrodynamic Simulation:** Set up and executed a 2D flood routing model using BASEMENT to capture complex, out-of-bank surface water flows and large-scale inundation dynamics.
* **Hydraulic Structures Integration:** Successfully modeled specialized hydraulic structures by implementing inner boundary conditions for weirs, allowing for accurate simulation of localized flood behavior and backwater effects.
* **Hazard & Velocity Mapping:** Conducted advanced geospatial analysis in QGIS to interpret flow velocity vectors, track water depth variations, and generate high-resolution flood extent maps.

## Tools & Technologies Used
* **HEC-RAS:** 1D hydrodynamic simulation of the river channel network.
* **BASEMENT (ETH Zürich):** 2D numerical modeling for surface flow and flood mapping.
* **QGIS:** Spatial data preparation, mesh configuration, and visual analysis of simulation outputs.

## Project Structure
* `/geometry_data` : Cross-section data, shapefiles, and terrain DEMs.
* `/models` : HEC-RAS project files and BASEMENT setup configurations (`.json` or command files).
* `/output_maps` : Exported flood hazard map layouts, depth rasters, and velocity profiles.
