## 3D Model of Andhra University college of Engineering campus

:boom: [Demo](https://venkanna37.github.io/3D_college_campus/)

_____________________________________________________________________________________________________________________________

### Usage

**Mouse**

Left button + Move	Orbit

Middle button + Move	Zoom

Right button + Move	Pan

**Keys**

Arrow keys	Move Horizontally

Shift + Arrow keys	Orbit

Ctrl + Arrow keys	Rotate

Shift + Ctrl + Up / Down	Zoom In / Out

R	Auto Rotate On / Off

U	Switch Upside Down

I	Show Information About Page

L	Toggle Label Visibility

W	Wireframe Mode

Shift + R	Reset View

Shift + S	Save Image

_____________________________________________________________________________________________________________________________

This 3D model is created using tools in **QGIS** software and **OpenStreetMap** data

**OpenStreetMap Data**

OpenStreetMap is built by a community of mappers that contribute and maintain data about roads, Buildings, trails, cafés, railway stations, and much more, all over the world.

OpenStreetMap is open data: you are free to use it for any purpose as long as you credit OpenStreetMap and its contributors.

**Tools used in QGIS**

1. OSMDownloader plugin
   - This plugin is used for downloading OSM data in college campus area, it is one of the easy way to download the OpenStreetMap data, but it downloads everything in selected area.
   - The format of this data is `.osm` so we have to convert this data into shapefiles for editing.
2. Openlayer plugin
   - This plugin is usefull editing OpenStreetMap data on QGIS desktop using various satellite image layers like Bing, Google, etc. and this plugin has many layers those we can open in QGIS Desktop.
3. Qgis2threejs plugin
   - This plugin is usefull for creating 3D features from shapefile data.
   - Using plugin we can create 3D objects like Sphere, Cube, Cylindar, Cone, Cuboid, Triangular Pyramid, Square pyramid and Triangular Prism, we can create these basic shapes using vector data. 
   - Based on these bacic shapes we can create various 3D features like Buildings, trees, benches, etc.
   - This plugin is using [threejs](http://threejs.org/) library for creating 3D model.
