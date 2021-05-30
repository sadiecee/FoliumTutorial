# The Basics of Crafting Static and Interactive Maps with Folium in Python
_Created by Sadie Murray._

## Background 
This tutorial will take you through how to use [Folium](https://python-visualization.github.io/folium/) to create static and interactive maps. Folium uses the mapping capabilities of the `leaflet.js`, a javascript mapping library that is designed with "simplicity, useability and performance" in mind. `Folium` brings the mapping capacity of `leaflet` to python. `Folium` lets you create interactive maps from data that has been manipulated in python, pass raster or vector markers in for use, and lets you bind data to chloropleth maps. The tutorial will take you through uploading and manipulating your data in python and creating customizable interactive maps, including chloropleth maps. 

Before we get started, it's important to mention that `folium` uses the `pandas` dataframe. The `pandas` dataframe is a python library used for mapping. To learn more about Pandas data structures, you can read up it [here](https://pandas.pydata.org/pandas-docs/stable/user_guide/dsintro.html). If you want to learn more about using the `pandas` library, you can follow [this tutorial](https://github.com/comorehouse1620/Matplotlib) before returning to this one. 

### Objectives
The main objective of this lab is to understand how to use the `folium` library, and to gain a deeper understanding of chloropleth maps. 

### What You Need To Begin
1. This tutorial is set up using Google Colabs, so you will need an account 
2. You will need to install [Pandas](https://pandas.pydata.org/), [Folium](https://python-visualization.github.io/folium/), and [JSON](https://docs.python.org/3/library/json.html) libraries
3. You will need to download the data located in this repos "Data" file and data from the site itself

Use the following code to install Pandas, Folium, and JSON libraries: 

```Python
import folium
import pandas as pd
import json
from folium import plugins
```

## Downloading the Data 
Some of the housing data we are going to be using in this tutorial is too big for the repo here, so you're going to need to download the files directly from ArcGIS Online hub that stores the HUD products. 


### Housing Crisis

For this tutorial, we will be using data from the US Department of Housing and Urban Development (HUD) to look at some questions of access to affordable, public housing. You can find all the data sets located in the "Data" folder of this repo, or you can download them yourself here: [Estimated Housing Authority Service Areas](https://hudgis-hud.opendata.arcgis.com/datasets/HUD::estimated-housing-authority-service-areas/about), and [Public Housing Buildings](https://hudgis-hud.opendata.arcgis.com/datasets/HUD::estimated-housing-authority-service-areas/about). 

The Estimated Housing Authority Service Area is polygon based data, where the data is aggregated and summarized at the "service areas" created by HUD themselves. The second dataset, Public Housing Buildings, is point based data, with each point representing a public housing building. We will look at how to explore both types of data in this tutorial. 

The data was downloaded in a CSV format for the Public Housing Buildings. It looks like: 
![](CSV_example.PNG)

```Python
# Upload local script to Colab - running this creates a "choose file" button to upload local files.
from google.colab import files
uploaded = files.upload()
```

## Using Folium 

### Static Maps 

### Interactive Maps 

### Cholorpleth Maps 

## Citation 
