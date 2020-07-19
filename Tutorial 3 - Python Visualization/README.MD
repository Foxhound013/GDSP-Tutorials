# Tutorial 3 Python Visualization
Welcome to the third tutorial in this series! In this section we're going to be covering the basics of Python visualization with a focus on Seaborns (and by extension Matplotlib). I highly recommend revisiting this section once you progress a little farther in your learning and seeing what all you can cook up with regards to plots. Visualization is one of the most powerful, if not the most powerful, tools you have to aid yourself in understanding your data and representing it to others. Good visualizations can be key to solid scientific discoveries so don't slack on this!

So, why seaborn over other popular plotting libraries in Python like Bokeh, Plotly, or even the grandaddy of them all Matplotlib? That's a great question. Seaborn is built on top of Matplotlib so you get some of that flexibility but seaborn barrows some ideas that are quite common in the R Lattice and ggplot2 worlds and makes it very easy to condition your plots. For example you can make a scatterplot conditioned on a particular aspect of your data and seaborn will split the data out into two seperate scatterplots making the relationships very easy to visualize with multiple dimensions. Used well, this is an amazingly powerful tool.

In the original version of this course (V1) there is a notebook that goes over matplotlib. If you're interested, feel free to check it out. If you intend to only use seaborn, it still wouldn't be a waste of time since seaborn is built on top of matplotlib.

Before starting this tutorial, you'll need to install seaborn which will install matplotlib as well since it is a dependency.

## Note
If you are an R user and really enjoy using lattice or ggplot and you want to use those in your Python code, you most certainly can! Check out the r2py package if or when you get to that but don't consider it a priority right now. I personally have no experience in this realm. While we're on the topic, you can work in the other direction too! Reticulate is a package maintained by the RStudio team to run Python scripts from within an R session.

## Note 2
I recognize that in the process of getting into visualizations we'll start to get into things that we haven't touched on just yet, like dataframes. Don't worry too much about this. I think you'll be able to play along with the examples and even successfully toy with some of the graphics for now. We're going to touch on dataframes soon but my hope here was to get to some of the visuals as fast as possible.

## Resources
Many of these resources are for libraries outside of just Seaborn. As you get more comfortable, feel free to explore these options. Some of these options may fit the problem you're trying to work through better than Seaborn or Matplotlib alone.

- Documentation for the granddaddy of plotting, Matplotlib: https://matplotlib.org/
  - A cheat sheet is always a welcomed resource for this sort of thing: https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Python_Matplotlib_Cheat_Sheet.pdf
  - Color options in Matplotlib: https://matplotlib.org/2.0.2/examples/color/named_colors.html
  - A good stackoverflow question regarding the use of subplots, even in the case of one plot. This tripped me up for a while too, check it out: https://stackoverflow.com/questions/34162443/why-do-many-examples-use-fig-ax-plt-subplots-in-matplotlib-pyplot-python
  - The anatomy of Matplotlib figure: https://matplotlib.org/3.1.1/gallery/showcase/anatomy.html
- Documentation for seaborn, the statistical offspring of Matplotlib: https://seaborn.pydata.org/
  - As with matplotlib, there is a cheat sheet for seaborn: https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Python_Seaborn_Cheat_Sheet.pdf
- If you're into R, there is a version of ggplot for Python as well! Check out the documentation here: http://ggplot.yhathq.com/
  - Note: If its just the style of the styling of a ggplot that you want in your matplotlib plots, you can set themes! In this case, you would use the following snippet of code `plt.style.use('ggplot')`
- Since we'll be doing visualization, we should probably have a dataset to play with. In my searching I came across this great Medium article that lists out some great repositories for datasets. Check it out here: https://towardsdatascience.com/top-10-great-sites-with-free-data-sets-581ac8f6334

Interactive Plotting Resource(s)
- If you're into interactive plots, plotly has you covered. Documentation can be found here: https://plot.ly/python/
- Bokeh is another option, documentation can be found here: https://bokeh.pydata.org/en/latest/index.html
- Holoviews looks like it may be a good option for larger datasets: http://holoviews.org/index.html
- Note: You may not want to get **too** overly excited about the interactive plots from plotly and bokeh. My understanding is that they tend to struggle when you get too much data (which is pretty easy to do in the geosciences...). Plotly does seem to be trying to remedy this with WebGL instead of relying on D3.js (a JavaScript framework for visualization that plotly was built on top of). I'm unsure whether or not Bokeh is following a similar development path but I would imagine that it probably is. I'm unsure of how all of these handle bigger datasets but Holoviews seems like it may be more capable in the realm of bigger datasets.

- If you're curious about the landscape of Python Visualization, check that out here: https://www.anaconda.com/wp-content/uploads/2018/12/PythonVisLandscape.jpg