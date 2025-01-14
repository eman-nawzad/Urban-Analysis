# Interactive Map Analysis using Google Colab

This repository contains a Google Colab notebook that creates an interactive map for spatial analysis. The map includes various layers such as Local Climate Zones (LCZ), Land Use, NDVI, Urban Density, and Roads, allowing users to explore geospatial data interactively.

## Features
- **Interactive Map**: Visualize multiple geospatial layers using Folium.
- **Layer Descriptions**:
  - **LCZ Data**: Local Climate Zone data, displayed in blue.
  - **Land Use**: Land cover data, highlighted in lime green.
  - **NDVI**: Normalized Difference Vegetation Index, represented in orange.
  - **Urban Density**: Urban density data, shown in red.
  - **Roads**: Road network data, displayed in black.

## Repository Contents
- `interactive_map.ipynb`: The Google Colab notebook that generates the interactive map.
- Sample GeoJSON files for each dataset:
  - `LCZ.geojson`
  - `Land_Use.geojson`
  - `NDVIt.geojson`
  - `UrbanDensity.geojson`
  - `Roads.geojson`

## Requirements
Before running the notebook, ensure you have the following:
- A Google account to access Google Colab.
- GeoJSON files for the layers mentioned above.
- Python packages: `folium`, `geopandas`.

## Usage Instructions
1. **Clone the Repository**:
   ```bash
   git clone <(https://github.com/eman-nawzad/Urban-Analysis)>
   cd <Urban-Analysis>

   Upload the GeoJSON Files: Ensure that the GeoJSON files (LCZ.geojson, Land_Use.geojson, etc.) are available in the same directory as the notebook.

2.Open the Notebook:

Go to Google Colab.
Upload interactive_map.ipynb.
Run the Notebook:

Execute each cell in the notebook sequentially.
The map will be displayed interactively within Colab.
Explore the Layers:

Use the layer control on the map to toggle between different layers.
Analyze the data visually and customize the styles as needed.
Replicating the Analysis
To replicate the analysis:

Replace the sample GeoJSON files with your own geospatial datasets.
Update the file paths in the geojson_paths dictionary in the notebook.
Modify the style settings in the code to match your dataset requirements.
Notes
Ensure all GeoJSON files use the EPSG:4326 (WGS 84) coordinate reference system for compatibility.
For questions or issues, please create an issue in this repository.
License
This project is licensed under the MIT License.




