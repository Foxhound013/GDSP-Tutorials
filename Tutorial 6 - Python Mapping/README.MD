# Tutorial 6 - Python Mapping
Welcome to the sixth tutorial in this series. This is somewhat of a return to visualization but this time we've got a few more tools and its time to start dealing with some geographic information. It's very likely that you have some geospatial data you'll want to work with in Python. This tutorial will give you the tools to get started with that!

If you have a lot of GIS type tasks to do, I'd recommend checking out the following link as it has a lot of libraries that you might find useful in that regard. https://gisgeography.com/python-libraries-gis-mapping/.

There are two major mapping libraries in Python, Basemap and Cartopy. Basemap has been deprecated in favor of Cartopy. We will cover some of the basics of cartopy in hopes of making it that much quicker for you to pick up and use in your own work!

Before starting this tutorial you'll need to install Cartopy. 

We'll be working with some geographic data from the Iowa Environmental Mesonet's archive of ASOS data which is available here: https://mesonet.agron.iastate.edu/request/download.phtml?network=IN_ASOS.

## Note
Another library that I came across in developing this tutorial is called GeoPandas. This seems like it could be a great alternative to Cartopy. We won't cover it here but I highly recommend checking it out. I know I will when I have more time to do so.

## Resources
 - A mapping example from the Cartopy documentation, this example serves as a basis for our tutorial: https://scitools.org.uk/cartopy/docs/v0.13/matplotlib/advanced_plotting.html
 - A great resource from Esri on coordinate reference systems and projections: https://pro.arcgis.com/en/pro-app/help/mapping/properties/specify-a-coordinate-system.htm#:~:text=A%20coordinate%20system%20is%20a,are%20relative%20to%20a%20surface
 - More information on coordinate reference systems from rspatial documentation, despite it being for R it still applies to the topic at hand. Check it out: https://rspatial.org/raster/spatial/6-crs.html
 - An example of faceted maps using seaborn and cartopy: https://gist.github.com/shoyer/16db9cd187886a3effd8
