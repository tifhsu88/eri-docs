# load_file

**load_file(path, resizeTo=None)**
- Read in .tif file, convert to numpy array, return the image as a numpy array

    - **Parameters:**
      	- path : *string*
      	  	- Path to .tif file
      	- resizeTo: *ndarray*
      	  	- Resize image
    - **Returns:**
      	- out: *array*
      	  	- 3d array containing each band, x, y dimensions
