# Google-Map-Generator
a Lib to create Google Maps easy way


## 1- Attach Google Map File
<script src="https://maps.googleapis.com/maps/api/js?v=3.exp&sensor=false"></script> 

## 2- Attach Google Map Generator
<script src="js/googleMapGenerator.js"></script> 

## 3- Init Function

var GoogleMapGen = new GoogleMapGenerator("YOUR_CONTAINER_ID", "WIDTH", "HEIGHT", LAT, LAG, "", [POINTER_LAT, POINTER_LAG, "POINTER_IMAGE"], ZOOM, CONTROLS, 'CUSTOM_THEME');
GoogleMapGen.init();
