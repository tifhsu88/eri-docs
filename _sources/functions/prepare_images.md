# prepare_images

**prepare_images(api_key, mosaic_name, directory, aoi_name, geojson_path)**
- Downloads cropped mosaic image from given AOI coordinates
    - **Parameters:**
      	- api_key : *string*
      	  	- Your Planet API key
      	- mosaic_name : *string*
      	  	- The name of the Planet basemap mosaic to search from
      	- directory : *string*
      	  	- Path to where quads are saved
      	- aoi_name : *string*
      	  	- Name to be given to merged and cropped TIF files
      	- geojson_path : *string*
      	  	- Path to geojson file of desired AOI
    - **Returns:**
      	- *none*
