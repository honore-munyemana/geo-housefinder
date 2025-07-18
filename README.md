# 🛰️ geo-housefinder

A deep learning pipeline to detect houses in drone orthophotos using YOLOv8, and convert results to GIS-ready shapefiles.

## 📁 Folder Structure

- `data/`: raw drone images + labels  
- `scripts/`: helper scripts (e.g., converters)  
- `training/`: YOLO training runs  
- `inference/`: predictions  
- `shapefiles/`: exported GeoJSON or .shp  
- `docs/`: documentation  

## ⚙️ Requirements

- Python 3.10  
- Ultralytics YOLOv8  
- GeoPandas, Rasterio, Shapely
