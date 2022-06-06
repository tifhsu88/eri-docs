# Data Augmentation

### In this step, we will break down the process of augmenting our data. 

Before the data augmentation process, we first need to convert the JSON annotations to binary masks.  To do so, input the path to the JSON file into the binary_mask() function (github).  This function will return a list of binary masks converted from all of the annotated images in your project.

Next, each raw image and label pair goes through the dataset.py file. This file splits and augments each image and label pair into chips decided by the chip size. It first generates a sliding window over each pair, then augments each window and saves each image. Each window is rotated (90, 180, 270) then each is flipped (horizontally, vertically) to multiply the original window by 12 times. 

```{note}
Any window with no labeled pixel would not be saved. This can be changed by removing the call to chip_is_empty(). 
```

Every chip is then saved as .tif files in the specified directory. Each image and label pair should have the same base file name. The image should end with `_mosaic.tif` and the label should end with `_label.tif`. The data is now ready for training.
