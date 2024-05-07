# CS579-Project-2

## Project Overview

This projects analyzes how the distribution of traffic lights and speed cameras in the City of Chicago affect the distribution of  speed-related car crashes. We use 3 datasets: Chicago Car Crashes, Chicago Speed Camera Locations, and Chicago Traffic Light Locations.

We collected the crash and speed camera datasets from the Chicago Data Portal, and the traffic light data was queried from OpenStreetMap. 

## Folder and File Layout

Datasets can be found in the [Data](https://github.com/BlueOceanWave/CS579-Project-2/blob/main/Data) folder

Graphs and visualizations can be found in [Graphs](https://github.com/BlueOceanWave/CS579-Project-2/blob/main/Graphs) folder

[traffic-lights-analysis.ipynb](https://github.com/BlueOceanWave/CS579-Project-2/blob/main/traffic-lights-analysis.ipynb) is the main file. It collects and processes the traffic light data, and it also performs speed camera analysis

[crash-preprocessing.ipynb](https://github.com/BlueOceanWave/CS579-Project-2/blob/main/crash-preprocessing.ipynb) filters the crash dataset for only speed-related crashes and displays a graph of them

[speed-camera-graph.ipynb](https://github.com/BlueOceanWave/CS579-Project-2/blob/main/speed-camera-graph.ipynb) overlays speed camera locations on top of the crashes