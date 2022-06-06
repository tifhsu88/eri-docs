# gen_data

**gen_data(images_dir, labels_dir, output_path, chip_size=256, channels=4, augment=False)**
- Chip and augment raw image/label pairs. Stores the image/label pairs assingle files. Note: the raw images and labels must be named the same and in different folders

    - **Parameters:**
      	- images_dir: *string*
      	  	- Directory to where raw images are placed
      	- labels_dir : *string*
      	  	- Directory to where labels are placed
      	- output_path : *string*
      	  	- Directory to where augmented image/label pairs will be saved
      	- chip_size: *int*
      	  	- Length of size to chip image to
      	- channels : *int*
      	  	- Number of channels the image data contains
      	- augment : *bool*
      	  	- if True, augments (flips and rotates) each chip
    - **Returns:**
      	- yield: *tuple*: (int, int, array)
      	    - Yields x coordinate, y coordinate, chipped image as a tuple
