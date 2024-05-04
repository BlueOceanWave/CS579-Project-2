# CS579-Project-2

## Project Overview

This projects analyzes how the distribution of traffic lights and speed cameras in the City of Chicago affect the distribution of  speed-related car crashes. We use 3 datasets: Chicago Car Crashes, Chicago Speed Camera Locations, and Chicago Traffic Light Locations.

We collected the crash and speed camera datasets from the Chicago Data Portal, and the traffic light data was queried from OpenStreetMap. 

## Folder and File Layout

Datasets can be found in the `Data` folder

Graphs and visualizations can be found in `Graphs` folder

`traffic-lights-analysis` is the main file. It collects and processes the traffic light data, and it also performs speed camera analysis

`crash-preprocessing` filters the crash dataset for only speed-related crashes and displays a graph of them

`speed-camera-graph` overlays speed camera locations on top of the crashes