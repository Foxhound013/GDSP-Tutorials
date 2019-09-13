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
- Datacamp is chalk full of excellent tutorials tailored for Data Science. They teach quite a few tutorials on Python and R: https://www.datacamp.com/

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
- What are lists, tuples, and dictionaries? 
- How are each of these different and under what circumstances should I use each? 
- How do I interact with these different data structures?
- What is Numpy?
- How do I work with Numpy?

If we can't finish this lesson in time, we'll continue where we left off for Tutorial 4. This document will be update to reflect such a scenario with listings for **Tutorial 3a** and **Tutorial 3b**

### Tutorial 4 - A Deep Dive on Pandas and Introduction to Scipy.
TO BE COMPLETED

### Tutorial 5 - Visualization Libraries and the Basics of Visualization
TO BE COMPLETED

### Tutorial 6 - Alternative to Pandas: Dask
TO BE COMPLETED

### Tutorial 7 - To Be Determined. Maybe PySpark?
TO BE COMPLETED

