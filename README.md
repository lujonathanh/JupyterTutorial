# JupyterTutorial

# Installation and Setup

If you'd like to follow along, you should first install Python 2.7. (note if you have Mac OS X, Python should come with your computer already)


You have several options:

1. [The Anaconda Installation](https://www.continuum.io/downloads) This will automatically install python, as well as much of the data analysis libraries we'll use.
2. [Normal Python Installation](https://www.python.org/downloads/) __Then follow the below steps:__
  1. Install __[pip](https://pip.pypa.io/en/stable/installing/)__, a program that manages the Python libraries you install.
  2. Install libraries numpy, scipy, and matplotlib, by running in the terminal:
    1. `pip install numpy`
    2. `pip install scipy`
    3. `pip install matplotlib`

Then, [install Jupyter Notebook](http://jupyter.readthedocs.io/en/latest/install.html). __If you use pip, run pip2, not pip3__.


# Notebook Download

Then, download the directory available at https://github.com/lujonathanh/JupyterTutorial.

Unzip this to a folder from which you'd like to run your code, like `tutorial`.

Then, open up your terminal and change directories into the JupyterTutorial folder. If your folder is named `tutorial`, then switch into `tutorial/JupyterTutorial`.

Then, from the command line, run the command: `jupyter notebook`

__If you are using anaconda, run: `jupyter-notebook` instead.__
