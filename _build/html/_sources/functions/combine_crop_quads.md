# combine_crop_quads

**combine_crop_quads(directory, aoi_name, geojson_path)**
- Merges quads in the given directory and crops to fit AOI coordinates. Downloads the merged and the cropped TIF files in the current working directory
    - **Parameters:**
      	- directory : *string*
      	  	- Path to where quads are saved
      	- aoi_name : *string*
      	  	- Name to be given to merged and cropped TIF files
      	- geojson_path : *string*
      	  	- Path to geojson file of desired AOI
    - **Returns:**
      	- *none*
