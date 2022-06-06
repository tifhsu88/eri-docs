# save_label

**save_label(data, path, area_name, x, y, augment_num = 0)**
- Save label as a .tif
    - **Parameters:**
      	- data: *array*
      	  	- 3d array image label
      	- path : *string*
      	  	- Base path to save the label
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
