# CIC - Carpentries Python Material

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/CurtinIC/CIC_Carpentries_Python/master)


## Schedule

1. Introduction to to the workshop and tools - [google slides](https://docs.google.com/presentation/d/1ccPobtWSwACLhfsf71ut2ZYLglCq2HoWn8ehLrv5mtw/edit?usp=sharing)
2. Introduction to Python
3. Data exploration and visualisation using Pandas
4. Automating tasks

## Create a conda environment for the workshop (optional)

Anaconda includes an environment manager called conda. Environments allow you to have multiple sets of Python packages installed at the same time, making reproducibility and upgrades easier. You can create, export, list, remove, and update environments that have different versions of Python and/or packages installed in them.

You can create a conda environment for this workshop using the provided yml file. The python version and all needed packages are listed in the environment.yml file.

**Using the command line**

On Mac or Linux, open your terminal, on Windows, open the Anaconda Prompt terminal app.

Now navigate to this repository directory in the terminal. For example, if you installed the CIC_Carpentries_Python repository on your Desktop, you could type the following.

On a Mac/Linux:
```
% cd Desktop/CIC_Carpentries_Python/
```
On Windows:
```
% cd Desktop\CIC_Carpentries_Python\
```
And finally, on any platform, to install and activate the CIC_Carpentries_Python environment, type:
```
% conda env create -n astropy-workshop --file environment.yml
% conda activate astropy-workshop
```
Note, you will need conda version 4.6 and later. If you need to update your version use conda update conda.

*conda environment notes adapted from the astropy workshop [repo](https://github.com/astropy/astropy-workshop).

**Using Anaconda Navigator**

To use the Anaconda Navigator GUI, check the step by step guide at the end of the [google slides](https://docs.google.com/presentation/d/1ccPobtWSwACLhfsf71ut2ZYLglCq2HoWn8ehLrv5mtw/edit?usp=sharing) accompanying this workshop.


## Further Reading

- Using Anaconda for package management ([cheatsheet](https://conda.io/docs/_downloads/conda-cheatsheet.pdf)) and [setting up environments](https://medium.com/datareply/working-with-python-environments-anaconda-package-manager-and-ides-663e771b6ed8)
- [Python](https://www.python.org/), and
- [Jupyter Notebooks](http://jupyter.org/)
