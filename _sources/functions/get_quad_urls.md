# get_quad_urls

**get_quad_urls(api_key, mosaic_name, aoi_coords)**
- Searches and returns list of metadata for the quads required to create a mosaic fitting the given AOI coordinates
    - **Parameters:**
      	- api_key : string
      	  	- Your Planet API key
      	- mosaic_name : string
      	  	- The name of the Planet basemap mosaic to search from
      	- aoi_coords : string
      	  	- String of AOI coordinates separated by commas
    - **Returns:**
      	- out: list
      	  	- List of quad metadata
