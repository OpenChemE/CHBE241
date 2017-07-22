[![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/UBC-Open-ChemE/Lobby)

# Useful Python tutorials by @corneliuscob

1. [__Code Academy__](https://www.codecademy.com/learn/python "Code Academy") has one of the better tutorials for python 
	- It is recommended	to go up to lesson 8 to grasp the general usage of python syntax, conditions and functions. 
	- Finish the entire python for more advanced concepts such as Object-Oriented Programming (this comes up in many other languages)
2. [__Jeff Kantor's__](http://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Getting%20Started%20with%20Jupyter%20Notebooks%20and%20Python.ipynb) intro to Jupyter also has a very quick and dirty  way of familiarizing yourself with the jupyter interface as well as work  with some of the features that Jeff implements into the notebook.
 	- Dowload Jeff's page by right-clicking the download button and click *save as* with the file suffix as .ipytnb
 	- Install [__Anaconda__](https://www.continuum.io/downloads), then run ```jupyter notebook``` from Anaconda's command prompt.
 	- Open the Jeff's page in your own notebook to play with the code.
 	- Shift-enter runs the code in every block segment of code.  
 3. [__This Data Analytics__](https://www.analyticsvidhya.com/blog/2016/01/complete-tutorial-learn-data-science-python-scratch-2/)
 Tutorial shows you step by step how to use the pandas library to analyze data and represent data.
 	- You can start the tutorial from the header _Importing libraries and the data set:_ in the jupyter notebook.
 4. [__Anacondas package installer__](https://www.continuum.io/blog/developer-blog/python-packages-and-environments-conda) is useful to download any packages not preinstalled onto your computer.
 	- [__Environments__](https://conda.io/docs/using/envs.html) are useful to run older versions of packages if there are compatibility issues.  
 	- on [__Jeff's__](http://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Getting%20Started%20with%20Units%20and%20Engineering%20Calculations.ipynb) page, he asks you to use ```pip install pint``` 
	but if you use ```conda list```, you can see that pint is a package in the conda library and can use conda to install it.
	- Using Pip is the alternative if the package is not in Conda.
5.  [**sphinx**](http://www.sphinx-doc.org/en/stable/) can be used to generate an online textbook like [this one](https://clouds.eos.ubc.ca/~phil/courses/parallel_python/) that's also exportable as a nice PDF document, all from the ipynb files.
