# save_image

**save_image(data, path, area_name, x, y, augment_num = 0)**
- Save chip as a .tif
    - **Parameters:**
      	- data: *array*
      	  	- 3d array image chip
      	- path : *string*
      	  	- Base path to save the image
      	- area_name : *string*
      	  	- Name of the area. Used in saved file name
      	- x: *int*
      	  	- x coordinate of chip. Used in saved file name
      	- y : *int*
      	  	- y coordinate of chip. Used in saved file name
      	- augment_num : *int*
      	  	- Index of an augmented chip. Used in saved file name
    - **Returns:**
      	- out: *none*
