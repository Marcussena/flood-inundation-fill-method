# flood-inundation-fill-method
# 🌊 Exploratory Flood Inundation Model with Python
This project demonstrates a simple flood simulation using a Digital Elevation Model (DEM) and a flood fill approach. It visualizes how rising water levels affect a terrain over time, using Python libraries such as rasterio, matplotlib, and numpy.

# 🚀 Features
- Loads and processes DEM files

- Handles no-data values gracefully

- Simulates inundation using elevation thresholds

- Animates flood progression over a specified area

- Customizable parameters (flood height, interval, etc.)

# 🗺️ Data Source
The example uses SRTM DEM data, freely available from the USGS National Map. The data used here is in the WGS84 coordinate system (EPSG:4326).

# 📦 Requirements
Python 3.8+

- rasterio

- numpy

- matplotlib

Install dependencies with:

```pip install rasterio numpy matplotlib```
# 📂 Usage
Run the main script:

```python flood_model.py```

### Customize the DEM file path, flood levels, or animation parameters directly in the script.

# 📽️ Output
The script generates an animated visualization showing how floodwaters rise across the terrain. The animation can also be saved as a GIF.
