# DMA Mapping with Plotly

This project explore's Plotly's features in regards to mapping custom regions. This project maps US DMA's and creates choropleths for each DMA region.

The project loads a GeoJson file containing the specified regions and maps out each region and colors each region according to a region's performance via a separate data source.

## Install the following libraries and the rest of these library's dependencies

* plotly
* pandas
* shapely

If using Jupyter Lab, make sure plotly is [installed properly](https://github.com/plotly/plotly.py#jupyterlab-support-python-35)

## Other Notes

Shape files and any other Geospatial file can be used as well to load coordinates. Geopandas would the library to use to easily load and manipulate these files. Once these coordinates are loaded, the process to mapping these custom regions would be the same.
