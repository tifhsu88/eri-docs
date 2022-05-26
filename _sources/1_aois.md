# Finding AOIs

For our project, the Areas of Interest, or **AOIs**, are images of center pivots from across the world. We aim to compile a diverse dataset composed of center pivots varying in size and color to optimize the model performance. 

In order to pull images through Planet Lab’s API, we have to first specify the coordinates of the specified area. The file format we use is a *GeoJSON* file, which encodes geographic data features while maintaining non-spatial attributes. 

To begin accumulating coordinates in the GeoJSON format, navigate to [geojson.io](geojson.io). Then switch to satellite view and begin the search for center pivots! 

```{note}
Center pivots are generally located around bodies of water. Once you have located the area of interest, select the *rectangle* selection tool and outline the area. The coordinates should pop up on the right hand side. 
```

![geojson_demo](geojson_demo.gif)

Proceed to the [next step](https://tifhsu88.github.io/eri-docs/2_planet_api.html) to learn how to use the collected coordinates to pull images from the PlanetLab API!
