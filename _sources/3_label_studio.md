# Annotating Images

### In this step, we will break down the process of setting up Label Studio, importing an image, and labeling the image. 


```{note}
**Label Studio** 
[Label Studio](https://labelstud.io) is an open source data labeling tool that allows users to label images, audio, text, and videos.
```

- Start off by installing Label Studio on your computer. Head to their [documentation](https://labelstud.io/guide/index.html)  to check out their quickstart directions!
- After creating an account, launch Label Studio and create a new project. 

![label-studio-label-settings](images/label_studio_label_settings.png)

- Then, create a label name called “Center Pivot.”
- Now we can begin labeling!
    - Begin by importing the .tif image you pulled from the Planet Lab API notebook. Then select the **Center Pivot** label and use the **ellipse region** tool to create a label for each center pivot. 

```{note}

For our project, we only focused on identifying full center pivots, regardless of whether it is active or not. In the future, we plan to begin integrating partial center pivots (look like pacmans) as well as classifying between active and inactive pivots.
```
![label-studio-demo](label-studio-demo.gif)

- Once you’re done annotating each pivot, save your changes and return to the home page to export the labeled images in the JSON-MIN format. 

![label-studio-export-instructions](images/label_studio_export)

