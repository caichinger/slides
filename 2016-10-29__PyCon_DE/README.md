# Python for Mathematics, Science and Engineering
## An Introduction to Python's Scientific Stack
### Abstract
This workshop gives a short overview of the Scientific Computing ecosystem in 
Python and what kind of problems it can be applied to.

In recent years, Python's scientific stack has emerged as a serious open source 
alternative to established proprietary systems like [MATLAB](http://matlab.com/) 
or specialized solutions like [R](https://www.r-project.org/). However, the wide
 range of packages and options is often confusing for inexperienced users - this
 talk aims to provide a remedy.

After a general introduction to the topic we will together
- apply [SciPy](http://scipy.org/scipylib/index.html) to solve a 
[predator-prey equation system](https://en.wikipedia.org/wiki/Lotka%E2%80%93Volterra_equations) 
to understand the dynamics of an ecological system,
- explore a wage data set using [pandas](http://pandas.pydata.org/) and 
[matplotlib](http://matplotlib.org/)/[seaborn](https://seaborn.github.io/) to 
learn about the influence of age and education on income and
- (if we have time ;)) try our hands on a simple machine learning task using 
[scikit-learn](http://scikit-learn.org/).

By the end of the workshop you will know how to get started with Scientific 
Computing in Python and have seen some of the major libraries in action. The 
[Jupyter](http://jupyter.org/) project and the scientific distributions 
[anaconda](https://www.continuum.io/anaconda-overview) and 
[WinPython](http://winpython.github.io/) are briefly presented.


**Target audience:** newcomers and beginners

### Technical Requirements
We will work with Python 3 and make use of the following libraries/tools:
- IPython, Jupyter Notebook, IPython Widgets, (Spyder, optional)
- numpy
- scipy
- pandas
- matplotlib
- seaborn
- scikit-learn

For new users, I **highly recommend** using a scientific distribution to install 
the required packages:
- [Anaconda](http://continuum.io/downloads) (cross-platform) or
- [WinPython](http://winpython.github.io/) (only Windows, no installation 
required).
Choose the lastest Python 3 version. Both ship with all required packages. 

If you already use conda, you can create (and activate) a suitable environment 
like so (`anaconda3/bin` needs to be in your `PATH` variable):
```
conda create --name scipy_workshop python=3.5 numpy scipy matplotlib pandas seaborn scikit-learn spyder jupyter ipywidgets
source activate scipy_workshop  # (Linux, Mac)
activate scipy_workshop  # (Windows)
# that's it; to deactivate this environment, use:
source deactivate scipy_workshop  # (Linux, Mac)
deactivate scipy_workshop  # (Windows)
```

For one visualization in the the machine learing example you need to have 
[Graphviz](http://www.graphviz.org/) installed on your system.


Please make sure you have your system set up prior to the workshop.


### Workshop Material
The data sets are taken from:
- **Wage**: taken from https://cran.r-project.org/web/packages/ISLR/index.html
- **Heart**: taken from http://www-bcf.usc.edu/~gareth/ISL/Heart.csv
