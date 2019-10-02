# GDSP-Tutorials
This repository serves as a home for all tutorials developed by myself for Purdue's GeoData Science for Professionals (GDSP) Masters of Science Program. The tutorials and order in which they are to be taught can be found below.

## Potentially Useful Tools
The following items are some tools that you may find useful in your time working with Python.

- PyCharm: This is a full fledged IDE (Integrated Development Environment). I've worked with it some and its an excellent tool. The community edition lacks the ability to SSH into remote servers and work on the code remotely though. For projects on a personal machine though, I can't recommend it enough. https://www.jetbrains.com/pycharm/
- VS Code: Visual Studio Code is a text editor by microsoft. You can configure this tool with a slew of extensions (some of which I will try to cover in one of our sessions). You can work on a multitude of languages with this text editor and SSH into one of the campus clusters to work on your code remotely. https://code.visualstudio.com/

## General Resources
Any resources that don't have a clear home in the following tutorials that I still think are useful will reside here.

- If you want to use a desktop session for Purdue's clusters, I'd recommend using the thinlinc client. It tends to be a little smoother than running it from a browser. https://www.cendio.com/thinlinc/download

## Python Basics
After speaking with some of those in the course, it seemed good to me to include some more general resources for learning Python. If you've never picked up Python before checkout the following links. Use as little or as much of each of these as you feel is necessary. The goal of these resources is to get you up to speed on how to write Python code at all. Some of these can be a little slow but if you stick with them, I'm sure you'll learn what you need to get off the ground.

- A tutorial from freecodecamp on starting out with Python: https://www.youtube.com/watch?v=rfscVS0vtbw
- Information on Python Packages: https://pypi.org/

- Interactive online tutorials/practice:
  - Datacamp is chalk full of excellent tutorials tailored for Data Science. They teach quite a few tutorials on Python and R: https://www.datacamp.com
  - Dataquest is much like datacamp in that it is tailored to data science: https://app.dataquest.io/today
  - There are a plethora of nanodegrees out there for Python, here is one: https://www.udacity.com/course/programming-for-data-science-nanodegree--nd104
  - Codecademy is the place many have gotten started learning a language for the first time: https://www.codecademy.com/learn/learn-python
  - HackerRank is a great resource for learning Python basics. It has tons of code tests to try out, all of which are labeled with a difficulty. For better or worse, many employers use this sort of test to determine whether or not to bring you in for an in person interview. Practice here will definitely help you out in those areas and should provide plenty of fodder for self study: https://www.hackerrank.com
  - LeetCode is pretty similar to HackerRank. If you're looking to challenge yourself on algorithms or get practice with feedback, this is a good go to: https://leetcode.com

- A condensed list of basic syntax and commands: https://www.tutorialspoint.com/python/index.htm

- A cheatsheet of the commands commonly used in Python: https://www.pythonforbeginners.com/cheatsheet/python-cheat-sheets

## Tutorials

### Tutorial 1 - Introduction to Anaconda and Git
See the corresponding folder for the slide deck. I've included an excellent crash course on Git below. Don't stress too much about the many commands you can use with Git. Get the basics down and you'll learn the other commands as you need them.

Resource(s)
- An excellent crash course on Git's usage by Traversy Media: https://www.youtube.com/watch?v=SWYqp7iY_Tc
- A super simple guidline to getting going fast with Git. Just the basics and nothing else. https://rogerdudler.github.io/git-guide/

### Tutorial 2 - Introduction to Jupyter and Virtual Environments
This lesson will focus on a few things to help you get set up and prepared to start analyzing data in Python. I've listed out what we'll cover below.

- What is Jupyter Notebook?
  - How do you start Jupyter in your local environment?
  - How do I use Jupyter on Purdue's cluster?
  - Magics? Yup, we're doing sorcery now!
- What is a virtual Environment and why is it important?
  - Setting up virtual environments.  
- How should we keep our data science projects clean?

Resource(s)
- A talk from Pycon 2015 describing Jupyter Notebooks generally and covering the use of magics in Jupyter: https://www.youtube.com/watch?v=zxkdO07L29Q
- As your projects become more involved, you'll need to decide what your workflow is going to be in order to stay organized. This article covers exactly that and provides some useful tips on how to manage all of your code and Jupyter Notebooks: https://medium.com/@rrfd/cookiecutter-data-science-organize-your-projects-atom-and-jupyter-2be7862f487e
- Speaking of cookie-cutter data science, here is the home page for the project. This site has a wealth of information on how to structure your data science work. Keep in mind, these aren't rules that must always be followed. You have the freedom to modify things as you see fit! https://drivendata.github.io/cookiecutter-data-science/
- While I **realy** like Jupyter Notebooks, they do have their limitations. It is a tool and just like any tool, it can be abused and misused. Jupyter Notebooks shine as a way to demonstrate an analysis and it's workflow, Exploratory Data Analysis (EDA), or for prototyping but when things get much more complicated you should consider pulling your code from the notebook into a regular Python project. https://towardsdatascience.com/5-reasons-why-jupyter-notebooks-suck-4dc201e27086

### Tutorial 3 - Data Structures in Python - The Basics to Numpy
This lesson is intended to take us back to the basics and build from there. We'll be answering the following questions . . .
- What are lists, sets, tuples, and dictionaries? 
- How are each of these different and under what circumstances should I use each? 
- How do I interact with these different data structures?
- What is Numpy?
- How do I work with Numpy?

Resource(s)
- Documentation on Python data structures: https://www.w3schools.com/python/python_lists.asp
- List comprehensions: https://medium.com/better-programming/list-comprehension-in-python-8895a785550b
- Info on sets: https://snakify.org/en/lessons/sets/
- Stackoverflow explanation of tuples: https://stackoverflow.com/a/2174236
- A good write up on dictionaries: https://medium.com/python-pandemonium/python-dictionaries-45cacc2b76aa
- A general introduction to Numpy: http://cs231n.github.io/python-numpy-tutorial/

### Tutorial 4 - Visualization Libraries and the Basics of Visualization
This lesson will be entirely focused on data visualization options in Python. With Python, you've got quite a few options for visualization. A quick Google search will turn up names like Bokeh, Matplotlib, Plotly, Seaborns, and probably quite a few more. We're going to focus on Matplotlib and Seaborns in Jupyter. This session won't be a deep dive on either of these libraries but it should be enough to get you up and going with them.

For this lesson, we're not going to get into the interactive options, there just isn't enough time. I'd encourage you to take a look at some of the interactive plotting libraries documentation and play around with some of them. We may try to cover interactive visualization options at a later time.

Resource(s)
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

### Tutorial 5 - A Deep Dive on Pandas and Introduction to Scipy.
TO BE COMPLETED

Resource(s)
- A general introduction to scipy: https://scipy-lectures.org/

### Tutorial 6 - Alternative to Pandas: Dask
TO BE COMPLETED

### Tutorial 7 - To Be Determined. Maybe PySpark?
TO BE COMPLETED

## Contributions

Due to some issues sorting out pull request with those attending the seminar workshops, I've included the Github accounts of contributors to this set of materials and their contributions.

https://github.com/avnikam : Provided a plethora of great online resources to aid fellow classmates in their learning.