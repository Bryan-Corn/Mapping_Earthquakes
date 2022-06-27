# Mapping_Earthquakes

Basic Project Plan
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

