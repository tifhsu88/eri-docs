# sliding_window

**sliding_window(image, step=(256, 256), window_size=(512, 512))**
- Generates a sliding window over an image. Each chip is determined by step size and window size

    - **Parameters:**
      	- image: *array*
      	  	- 3d array image/label
      	- step : *tuple*
      	  	- Tuple of (height, width) that determines step size
      	- window_size : *tuple*
      	  	- Tuple of (height, width) that determines window size
    - **Returns:**
      	- yield: *tuple*: (int, int, array)
      	    - Yields x coordinate, y coordinate, chipped image as a tuple
