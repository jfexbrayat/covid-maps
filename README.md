# covid-maps

This repository consists in notebooks that displays several Covid-19 relevant metrics from the Robert Koch Institute (RKI) for Germany at the district (*Landkreis*) level. 
Notebooks run from top to bottom to fetch geospatial data from the [German Federal Agency for Cartography and Geodesy](https://www.bkg.bund.de), Covid-19 metrics from the [RKI API](https://api.corona-zahlen.org/docs/) in interactive maps using:
- the [interactive plotting tool bokeh](https://bokeh.org/) `bokeh-covd.ipynb`
- the new `GeoDataFrame.explore` method from [geopandas version 0.10 and above](https://geopandas.org/en/stable/)

Notebooks were developed using Google Colaboratory and is runnable by following links at their top.
