# Tutorial 4 - Python Data Stack 1
Welcome to the fourth tutorial in this series. Today we'll be covering the first part of the Python scientific stack, numpy and scipy. These are the libraries that will underly just about everything when it comes to scientific work in Python (there are exceptions but that's not the point here).

Numpy is the powerful library that grants Python its vectorized super powers. It stands for Numerical Python. If you're familiar with R, think of Numpy as adding a lot of the functionality that R is built on top of already. For data analytics and scientific work, having access to vector operations is paramount to maintaining fast computation throughout the analysis.

Scipy is the primary library in Python for adding in common scientific mathematical operations. There is a huge variety of things you can do with Scipy including the following: clustering algorithms, Fast Fourier Transforms (FFT), integration, interpolation, various linear algebra operations, optimization, signal processing, and many others. Given how versatile scipy is and the situational nature of this library, we won't cover it here but I highly recommend checking out the official documentation if you have any needs met by scipy.

You'll notice this tutorial was titled as the Python Data Stack. There is a reason for that. A stack in programming typically refers to a set of tools used for a particular task. In this case, scientific work has a set of core libraries that it tends to use. For scientific work these libraries are Numpy (for vector operations), scipy (for many common mathematical operations), Pandas (we'll get to this in the next tutorial), and matplotlib/seaborn (for data visualization). This trio of packages make it possible to do a wide variety of scientific work and are very rarely missing from any scientific work performed in Python. It should be noted that other libraries definitely get used in scientific work but these are the ones that are hard to live/work without.

Before starting this tutorial, you'll need to install numpy, scipy, and pillow (pillow will allow us to view our image we're using in the numpy portion of this tutorial).

## Resources
- A general introduction to Numpy: http://cs231n.github.io/python-numpy-tutorial/
- The numpy documentation: https://docs.scipy.org/doc/numpy/reference/ 
- A wonderful cheat sheet from the folks over at Datacamp for Numpy: https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Numpy_Python_Cheat_Sheet.pdf
- Like just about anything else, Datacamp has a cheat sheet for Scipy as well: https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Python_SciPy_Cheat_Sheet_Linear_Algebra.pdf
