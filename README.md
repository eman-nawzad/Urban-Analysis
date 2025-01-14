# My Colab Project: Interactive Map

## Overview
This project demonstrates how to create an interactive map using multiple GeoJSON layers. The map includes data for:

- **Local Climate Zones (LCZ)**
- **Land Use**
- **NDVI (Vegetation Data)**
- **Urban Density**
- **Roads**

## Setup Instructions

### Prerequisites
- **Google Colab** (for running the notebook)
- **Python 3.x environment**

### Install Dependencies
To install the necessary libraries, run the following command:
```bash
pip install -r requirements.txt
```

### Running the Notebook
1. Clone this repository to your local machine or Colab environment:
   ```bash
   git clone https://github.com/eman-nawzad/Urban-Analysis.git
   ```

2. Navigate to the repository folder:
   ```bash
   cd Urban-Analysis
   ```

3. Open the `Urban_analysis.ipynb` notebook in Google Colab.

4. Execute the code cells. The interactive map will be displayed, allowing you to toggle between different layers (LCZ, Land Use, NDVI-DS, Urban Density, Roads).

## Data
The dataset files are stored in the `/data/` folder, and you can either use these directly or replace them with your own files. The required GeoJSON files are:

- `LCZ.geojson`
- `Land_Use.geojson`
- `NDVIt.geojson`
- `UrbanDensity.geojson`
- `Roads.geojson`

## Repository Structure
```
Urban-Analysis/
|— data/
|   |— LCZ.geojson
|   |— Land_Use.geojson
|   |— NDVIt.geojson
|   |— UrbanDensity.geojson
|   |— Roads.geojson
|— scripts/
|— Urban_analysis.ipynb
|— requirements.txt
|— README.md
|— LICENSE
|— .gitignore
```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.



