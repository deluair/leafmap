# Welcome to leafmap

[![image](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://demo.leafmap.org)
[![image](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/opengeos/leafmap/blob/master/examples/notebooks/00_key_features.ipynb)
[![image](https://img.shields.io/badge/Open-Planetary%20Computer-black?style=flat&logo=microsoft)](https://pccompute.westeurope.cloudapp.azure.com/compute/hub/user-redirect/git-pull?repo=https://github.com/opengeos/leafmap&urlpath=lab/tree/leafmap/examples/notebooks/00_key_features.ipynb&branch=master)
[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://gishub.org/leafmap-colab)
[![image](https://mybinder.org/badge_logo.svg)](https://gishub.org/leafmap-binder)
[![image](https://img.shields.io/pypi/v/leafmap.svg)](https://pypi.python.org/pypi/leafmap)
[![image](https://img.shields.io/conda/vn/conda-forge/leafmap.svg)](https://anaconda.org/conda-forge/leafmap)
[![image](https://pepy.tech/badge/leafmap)](https://pepy.tech/project/leafmap)
[![image](https://github.com/opengeos/leafmap/workflows/docs/badge.svg)](https://leafmap.org)
[![image](https://github.com/opengeos/leafmap/workflows/Linux%20build/badge.svg)](https://github.com/opengeos/leafmap/actions)
[![image](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![image](https://img.shields.io/badge/YouTube-Channel-red)](https://youtube.com/@giswqs)
[![status](https://joss.theoj.org/papers/10.21105/joss.03414/status.svg)](https://doi.org/10.21105/joss.03414)

[![logo](https://i.imgur.com/tekMHkz.png)](https://github.com/opengeos/leafmap/blob/master/docs/assets/logo.png)

**A Python package for geospatial analysis and interactive mapping in a Jupyter environment.**

-   GitHub repo: <https://github.com/opengeos/leafmap>
-   Documentation: <https://leafmap.org>
-   PyPI: <https://pypi.org/project/leafmap>
-   Conda-forge: <https://anaconda.org/conda-forge/leafmap>
-   Leafmap tutorials on YouTube: <https://youtube.com/@giswqs>
-   Free software: [MIT license](https://opensource.org/licenses/MIT)

## Introduction

**Leafmap** is a Python package for interactive mapping and geospatial analysis with minimal coding in a Jupyter environment. It is a spin-off project of the [geemap](https://geemap.org) Python package, which was designed specifically to work with [Google Earth Engine](https://earthengine.google.com) (GEE). However, not everyone in the geospatial community has access to the GEE cloud computing platform. Leafmap is designed to fill this gap for non-GEE users. It is a free and open-source Python package that enables users to analyze and visualize geospatial data with minimal coding in a Jupyter environment, such as Google Colab, Jupyter Notebook, and JupyterLab. Leafmap is built upon several open-source packages, such as [folium](https://github.com/python-visualization/folium) and [ipyleaflet](https://github.com/jupyter-widgets/ipyleaflet) (for creating interactive maps), [WhiteboxTools](https://github.com/jblindsay/whitebox-tools) and [whiteboxgui](https://github.com/opengeos/whiteboxgui) (for analyzing geospatial data), and [ipywidgets](https://github.com/jupyter-widgets/ipywidgets) (for designing interactive graphical user interface [GUI]). Leafmap has a toolset with various interactive tools that allow users to load vector and raster data onto the map without coding. In addition, users can use the powerful analytical backend (i.e., WhiteboxTools) to perform geospatial analysis directly within the leafmap user interface without writing a single line of code. The WhiteboxTools library currently contains **500+** tools for advanced geospatial analysis, such as [GIS Analysis](https://jblindsay.github.io/wbt_book/available_tools/gis_analysis.html), [Geomorphometric Analysis](https://jblindsay.github.io/wbt_book/available_tools/geomorphometric_analysis.html), [Hydrological Analysis](https://jblindsay.github.io/wbt_book/available_tools/hydrological_analysis.html), [LiDAR Data Analysis](https://jblindsay.github.io/wbt_book/available_tools/lidar_tools.html), [Mathematical and Statistical Analysis](https://jblindsay.github.io/wbt_book/available_tools/mathand_stats_tools.html), and [Stream Network Analysis](https://jblindsay.github.io/wbt_book/available_tools/stream_network_analysis.html).

## Statement of Need

There are a plethora of Python packages for geospatial analysis, such as [geopandas](https://github.com/geopandas/geopandas) for vector data analysis and [xarray](https://github.com/pydata/xarray) for raster data analysis. However, few Python packages provide interactive GUIs for loading geospatial data in a Jupyter environment. It might take many lines to code to load and display geospatial data with various file formats on an interactive map, which can be a challenging task for novice users with limited coding skills. There are also some notable Python packages for visualizing geospatial data in a Jupyter environment, such as [plotly](https://github.com/plotly/plotly.py) and [kepler.gl](https://docs.kepler.gl/docs/keplergl-jupyter). However, plotly is designed for displaying static data, which lacks bidirectional communication between the front-end and the backend. Kepler.gl provides unique 3D functionality for visualizing large-scale geospatial datasets, but it lacks tools for performing geospatial analysis, such as hydrological analysis and LiDAR data analysis. In contrast, leafmap provides many convenient functions for loading and visualizing geospatial datasets with only one line of code. Users can also use the interactive GUI to load geospatial datasets without coding. Leafmap is intended for anyone who would like to analyze and visualize geospatial data interactively in a Jupyter environment. It is particularly suited for novice users with limited programming skills. Advanced programmers can also find leafmap a useful tool for analyzing geospatial data and building interactive web apps.

Launch the interactive notebook tutorial for the **leafmap** Python package with JupyterLite, Google Colab, Binder, or Amazon Sagemaker Studio Lab now:

[![image](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://demo.leafmap.org)
[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://gishub.org/leafmap-colab)
[![image](https://mybinder.org/badge_logo.svg)](https://gishub.org/leafmap-binder)
[![Open In Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/opengeos/leafmap/blob/master/examples/notebooks/00_key_features.ipynb)

Check out this excellent article on Medium - [Leafmap a new Python Package for Geospatial data science](https://link.medium.com/HRRKDcynYgb)

To learn more about leafmap, check out the leafmap documentation website - <https://leafmap.org>

![](https://i.imgur.com/abd8pTH.gif)

## Key Features

Below is a partial list of features available for the leafmap package. Please check the [examples](https://github.com/opengeos/leafmap/tree/master/examples) page for notebook examples, GIF animations, and video tutorials.

-   Create an interactive map with only one-line of code.
-   Select from a variety of basemaps interactively without coding.
-   Add XYZ, WMS, and vector tile services to the map.
-   Convert CSV to points and display points as a marker cluster.
-   Add local vector data (e.g., shapefile, GeoJSON, KML) to the map without coding.
-   Add local raster data (e.g., GeoTIFF) to the map without coding.
-   Add Cloud Optimized GeoTIFF (COG) and SpatialTemporal Asset Catalog (STAC) to the map.
-   Add OpenStreetMap data to the map with a single line of code.
-   Add a GeoPandas GeoDataFrame to the map with a single line of code.
-   Add a point layer with popup attributes to the map.
-   Add data from a PostGIS database to the map.
-   Add custom legends and colorbars to the map.
-   Perform geospatial analysis using WhiteboxTools and whiteboxgui.
-   Create split-panel map and linked maps.
-   Publish interactive maps with a single line of code.
-   Download and display OpenStreetMap data with a single line of code.

## Citations

If you find **leafmap** useful in your research, please consider citing the following paper to support my work. Thank you for your support.

-   Wu, Q. (2021). Leafmap: A Python package for interactive mapping and geospatial analysis with minimal coding in a Jupyter environment. _Journal of Open Source Software_, 6(63), 3414. <https://doi.org/10.21105/joss.03414>

## Demo

![](https://wetlands.io/file/images/leafmap_demo.gif)

## YouTube Channel

I have created a [YouTube Channel](https://youtube.com/@giswqs) for sharing geospatial tutorials. You can subscribe to my channel for regular updates. If there is any specific tutorial you would like to see, please submit a feature request [here](https://github.com/opengeos/leafmap/issues).

[![Earth Engine Tutorials on YouTube](https://wetlands.io/file/images/youtube.png)](https://youtube.com/@giswqs)
