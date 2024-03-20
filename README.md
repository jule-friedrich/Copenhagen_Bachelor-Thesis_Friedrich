# Evaluating the Impact of Bicycle Bridges on the X-Minute City Concept in Copenhagen, Denmark

This repository contains the PDF as well as the data files that were used or created as part of the Bachelor Thesis "Evaluating the Impact of Bicycle Bridges on the X-Minute City concept in Copenhagen, Denmark" written by Jule Friedrich (submitted March 2024).

## Data sets
The datasets consist of the input data, the output data, as well as the models used to accelerate computing processes.
Datasets that consist of multiple shapefile layers are packaged as gpkg file.

The codification of layer files is displayed as **"name of geopackage"**: ["codification of layers"]

### Input Layers :
**Input Data_Amenity Point Layers**
- Amenity point layers used to create isochrones ["Amenity types"_points]
  
**Input Data General**
- Area of Interest
- Boundary Copenhagen Municipality
- Bounding Box (used to extract amenity data)
- bridge points layer [Bridges as Points]
- bridge polygons layer [Bridges as Polygons]
- point layer _buildings_ [Buildings as Points within Area of Interest]
- grid that consists of the residential cells within the area of interest [Grid_ Residential Cells within Area of Interest]
  
### Output Layers (Results):
- amenity based impact zone layers that contain the counted _building_ points.  **Counted Building Points Layers_Impact**: [Counted_amenity_threshold]
- amenity based initial accesbility that contains the counted _building_ points. **Counted Building Points Layers_Initial Access**: ["amenity type" No brigde min "threshold"]
- the final grid layers that display spatial distribution of initial, topical, and impacted accesibility. In the attribute tables the individual category grid layers are contained. **Grids Impact/Spatial/Topical**: [Grid_Initial/Topical/Impact_Threshold]

### Models
- The model used to create isocrones, symmetrical differences and count of buildings within impact zones [Model_ Creation of Isochrones and Counting of Buildings in Symmetrical Difference]
- The model used to create final grids by joining category layers [Model_Creation of final Grids by spatially joining Category Layers]


### Data Description
W - topical access ("With bridges")
N - initial access ("No Bridges")
D - impact on access ("Difference that bridges make")
3/ 5/ 10/ 15 -type of Threshold 

