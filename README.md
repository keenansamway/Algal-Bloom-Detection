# Algal-Bloom-Detection
 Driven Data Competition "Tick Tick Bloom: Harmful Algal Bloom Detection Challenge" hosted by NASA

## Classification Problem
- Classify the severity (1-5) of the 'test' split locations in the metadata.csv file

## Data Sources

### Satellite Imagery
- Sentinel-2 (10m resolution)
    - Mid-2016 onwards
    - Level-1C (L1C) via Google Earth Engine
    - Level-2A (L2A) via Google Earth Engine or Microsoft Planetary Computer
- Landsat (30m resolution)
    - Landsat 8 and Landsat 9 from March 2013 onwards
    - Landsat 7 for January and February 2013 only

### Climate Data 
- High-Resolution Rapid Refresh (HRRR) (3km resolution)

### Elevation Data (not used)
- Copernicus DEM (30m resolution)

## Model Inputs
- Satellite image
- Surface temperature