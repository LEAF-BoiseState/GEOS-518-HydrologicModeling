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
the bare minimum in terms of Python packages. Once you install Miniconda, you can use the following 
```conda``` commands at the commnd prompt to install the packages you need. In particular, when getting
started, I'd recommend:

* ```conda install numpy```
* ```conda install scipy```
* ```conda install pandas```
* ```conda install matplotlib```
* ```conda install xarray```

Additionally, you can install Jupyter using the following command:

* ```conda install jupyter```

If you like having an Integrated Development Environment (IDE, like Matlab's nice user interface), 
many folks like Spyder, which can be installed using, you guessed it,

* ```conda install spyder```



