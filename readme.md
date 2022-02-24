# Nearmap OpenLayers JavaScript Test

<b>The following is a standard JavaScript Test for new Nearmap Hires with JavaScript Experience.</b>

For this test you will leverage an existing App based on [OpenLayers](https://openlayers.org/)  <i> "A high-performance, feature-packed library for all your mapping needs."</i>

The incorporated test API Key limits the user experience to Austin Texas.
The focus will be around limiting the user experience to a single asset of interest. 
[The Frost Bank Building](https://upload.wikimedia.org/wikipedia/commons/d/dd/FrostTower-Feb2009.JPG)


<b>After forking this GitHub Repo you will incorporate Three additional operations</b>:

1.) Reading the included geojson file: "Frost_Bank_Building.geojson" as json and obtaining the building geometry on load-up.
- Adding the operation in config.js will suffice. <i> "Hint: use ```require()``` or ```fetch()```"</i>

2.) Constrain the map canvas navigation to cover the extent of the geojson geometry with your desired offset distance:
- Implement [Constrained Extent](https://openlayers.org/en/latest/examples/extent-constrained.html) <i>"Hint: you will need to first</i> [load the geometry](https://openlayers.org/en/latest/apidoc/module-ol_geom_Geometry-Geometry.html) and then [obtain the geometry four corners also known as bounds](https://openlayers.org/en/latest/apidoc/module-ol_extent.html)"
- Extra Credit: Implement [Constrained Zoom](https://openlayers.org/en/latest/examples/zoom-constrained.html). "Hint: Most required Math can be located [Here](https://wiki.openstreetmap.org/wiki/Zoom_levels) and combine with the [length and height of the extent](https://openlayers.org/en/latest/apidoc/module-ol_extent.html) to ensure the optimal zoom for complete asset coverage."

3.) Mask the imagery to the extent of the geometry from the "Frost_Bank_Building.geojson" geometry:
- Implement [Crop-Filter](https://viglino.github.io/ol-ext/examples/filter/map.filter.crop.html)

4.) Extra Credit: [Render the geometry outline](https://openlayers.org/en/latest/examples/render-geometry.html) on the map canvas.


Lastly you will commit and push your results to the forked GitHub Repo.

Once complete you will demonstrate the application and workflow in a follow-up call.

Happy Coding!

<b>The Nearmap Hiring Team </b>
