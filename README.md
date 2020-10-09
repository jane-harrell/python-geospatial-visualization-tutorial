# python-geospatial-visualization-tutorial

This tutorial provides an introduction to geospatial data visualization using Python. It covers some basic uses of the Python library GeoPandas followed by an introduction to some other useful and FUN Python libraries for more advanced visualization examples.

Tutorial Outline:

1. Introduction to Geopandas
2. Combining the functionality of Rasterio, Rasterstats, and Geopandas to process and visualize raster data
3. Interactive maps with Geoviews and Holoviews

Each of the libraries we will be using have unique dependencies. It is highly encouraged that you create a new conda environment to follow this tutorial. To create a new environment and install necessary libraries, in the terminal run the command:

`conda create -n myenv -c pyviz -c conda-forge geopandas descartes contextily mapclassify rasterio rasterstats geoviews holoviews nb_conda_kernels`

You can activate your new environment with the command:

`conda activate myenv`
 
**Let's make some maps!**
