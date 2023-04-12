![image](https://github.com/Bryan-Corn/Mapping_Earthquakes/blob/main/ReadMe_Images/Header.png)
# Mapping_Earthquakes

## Purpose

The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

## Tasks

A URL for GeoJSON earthquake data from the USGS website is used to retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days and the data is added to a map.

## Approach

Using JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data,  the Leaflet library plots the data on a Mapbox map through an API request and creates interactivity for the earthquake data.

## Use
A user can use this code by inserting their own API key in config.js.

## Notes
Overlays are drawn in the order they are selected. When all layers are selected in order, all the earthquakes are shown but the major ones are drawn over the fault lines.  The following screenshots are to show that this works on my machine.

![image](https://github.com/Bryan-Corn/Mapping_Earthquakes/blob/main/ReadMe_Images/Mapping_Earthquakes1.png)

![image](https://github.com/Bryan-Corn/Mapping_Earthquakes/blob/main/ReadMe_Images/Mapping_Earthquakes2.png)

![image](https://github.com/Bryan-Corn/Mapping_Earthquakes/blob/main/ReadMe_Images/Mapping_Earthquakes3.png)

![image](https://github.com/Bryan-Corn/Mapping_Earthquakes/blob/main/ReadMe_Images/Mapping_Earthquakes4.png)

![image](https://github.com/Bryan-Corn/Mapping_Earthquakes/blob/main/ReadMe_Images/Mapping_Earthquakes5.png)

![image](https://github.com/Bryan-Corn/Mapping_Earthquakes/blob/main/ReadMe_Images/Mapping_Earthquakes6.png)

![image](https://github.com/Bryan-Corn/Mapping_Earthquakes/blob/main/ReadMe_Images/Mapping_Earthquakes7.png)

![image](https://github.com/Bryan-Corn/Mapping_Earthquakes/blob/main/ReadMe_Images/Mapping_Earthquakes8.png)

![image](https://github.com/Bryan-Corn/Mapping_Earthquakes/blob/main/ReadMe_Images/Mapping_Earthquakes9.png)

![image](https://github.com/Bryan-Corn/Mapping_Earthquakes/blob/main/ReadMe_Images/Mapping_Earthquakes10.png)

In this last image, all layers were cleared and selected in order, rendering the fault lines over the total earthquakes layer but under the major earthquakes.


The following screenshots are to show that the popups work:

![image](https://github.com/Bryan-Corn/Mapping_Earthquakes/blob/main/ReadMe_Images/Mapping_Earthquakes11.png)

![image](https://github.com/Bryan-Corn/Mapping_Earthquakes/blob/main/ReadMe_Images/Mapping_Earthquakes12.png)
