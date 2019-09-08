# Unit 01: Scientific Computing Quick-start

## Introduction

This first unit of the workshop portion of Hydrologic Modeling focuses on some foundational concepts
in scientific computing. In particular, we will focus on the following core components of scientific 
computing: 

* The Unix Shell
* Version Control with Git
* Scientific Programming in Python

## Materials

We will be following Software Carpentry workshop materials that have been developed and maintained 
by The Carpentries for introducing learners to scientific programming. These materials have undergone
significant review to ensure that they use evidence-based pedagogical practices to foster an 
inclusive educational environment. 

The specific materials we will be using can be found in the links below. The materials are linked in 
the order in which we will use them. Feel free to review the materials in advance of our workshops, 
try exercises yourself, and/or use the materials after we cover the material in class workshops.

1. [The Unix Shell Lesson](http://swcarpentry.github.io/shell-novice/)
2. [Version Control with Git Lesson](http://swcarpentry.github.io/git-novice/)
3. [Programming with Python](http://swcarpentry.github.io/python-novice-inflammation/)

## Computational Sandbox

For these introductory lessons, we will use the [Boise State Jupyter Server](https://jupyter.boisestate.edu/). Note that these instances are not persistent. So, as soon as you close the tab that contains the Jupyter notebook instance you are using, all work and any files uploaded to the notebook will be lost permanently. 

## Setting Up Your Computing Environment (optional)

Jupyter Notebooks is fairly easy to install on your own laptop or desktop, however. For those 
that are just getting into scientific programming, I would strongly recommend that you install
Miniconda, a lightweight Python installation with the ```conda``` package manager. Miniconda is 
available for download for Windows, Mac, and Linux at no cost by [following this link](https://docs.conda.io/en/latest/miniconda.html). I highly recommend Miniconda (over Anaconda, 
PyTorch, and other development environments) because it is easy to install and only installs 
the bare minimum in terms of Python packages. __Make sure you install Python 3.x. Python 2.7 is no longer 
under active development and many packages no longer work with it.__ Once you install Miniconda, 
you can use the following ```conda``` commands at the commnd prompt to install the packages you need. 
In particular, when getting started, I'd recommend:

* ```conda install numpy```: Installs "numerical python," which is used for doing mathematical operations
* ```conda install scipy```: Installs "scientific python," which is used for additional scientific operations
* ```conda install ipython```: Installs "interactive python," which provides an interactive environment to work in. 
  This is exceptionally useful in data science applications.
* ```conda install pandas```: A very useful data science framework that allows for sophisticated query operations
  using "data frames." For those familiar with the ```R``` programming language, Pandas provides some very 
  similar high-level features like ```R```.
* ```conda install matplotlib```: A plotting package used for making a variety of plots
* ```conda install xarray```: An extremely powerful toolbox for multi-dimensional data analysis. We will use this
  toolbox extensively later in the class to analyze and plot input to and output from WRF-Hydro.

Additionally, you can install Jupyter using the following command:

* ```conda install jupyter```

If you like having an Integrated Development Environment (IDE, like Matlab's nice user interface), 
many folks like Spyder, which can be installed using, you guessed it,

* ```conda install spyder```

## Resources

For those interested, here is further documentation of these key toolboxes. You might want to review these and/or
bookmark them for future reference.

* [NumPy documentation](https://docs.scipy.org/doc/numpy/index.html)
* [SciPy documentation](https://docs.scipy.org/doc/scipy/reference/)
* [IPython documentation](https://ipython.readthedocs.io/en/stable/)
* [Pandas documentation](https://pandas.pydata.org/pandas-docs/stable/)
* [Matplotlib documentation](https://matplotlib.org/contents.html)
* [Xarray documentation](http://xarray.pydata.org/en/stable/)

Note that many of these toolboxes offer PDF versions of manuals. I __would not__ use them. All of these
libraries are under continuous development and, while not much changes from one release to the next, there can be 
subtle changes meaning that your PDF would be out of sync with your toolboxes/libraries as you update them.


