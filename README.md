# CIC - Carpentries Python Material

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/CurtinIC/CIC_Carpentries_Python/master)


## Schedule

1. Introduction to to the workshop and tools. [Slides link](https://docs.google.com/presentation/d/11251tEp-g5K2HC1zqes_lgwPKEzLLxruH3J8dwQfckI/edit#slide=id.g872ddefe8c_0_77)
2. Introduction to Python
3. Data exploration and visualisation using Pandas
4. Automating tasks

## Installing Anaconda

### Windows
- Open https://www.anaconda.com/distribution/#download-section with your web browser.
- Download the Anaconda for Windows installer with Python 3.9. (If you are not sure which version to choose, you probably want the 64-bit Graphical Installer)
- Install Python 3 by running the Anaconda Installer, using the recommended settings. **Make sure that Register Anaconda as my default Python 3.x option is checked – it should be in the latest version of Anaconda..**

## MacOS
- Open https://www.anaconda.com/distribution/#download-section with your web browser.
- Download the Anaconda Installer with Python 3.9 for macOS (You can either use the Graphical or the Command Line Installer).
- Follow the Anaconda Python 3 installation instructions. Make sure that the install location is set to “Install only for me” so Anaconda will install its files locally, relative to your home directory. Installing the software for all users tends to create problems in the long run and should be avoided.

## Linux
- Open https://www.anaconda.com/distribution/#download-section with your web browser.
- Download the Anaconda Installer with Python 3.9 for Linux (Select the 64-Bit (x86) Installer).

(The installation requires using the shell. If you aren't comfortable doing the installation yourself stop here and request help at the workshop.)
- Open a terminal window and navigate to the directory where the executable is downloaded (e.g., `cd ~/Downloads`).
- Type
```
bash Anaconda3-
```
- and then press **Tab** to autocomplete the full file name. The name of file you just downloaded should appear. Press Enter. 
- You will follow the text-only prompts. 
  - To move through the text, press **Spacebar**. 
  - Type yes and press enter to approve the license. 
  - Press **Enter** to approve the default location for the files. 
  - Type yes and press Enter to prepend Anaconda to your PATH (this makes the Anaconda distribution the default Python).
- Close the terminal window.

## Create a conda environment for the workshop (optional but recommended)

Anaconda includes an environment manager called conda. Environments allow you to have multiple sets of Python packages installed at the same time, making reproducibility and upgrades easier. You can create, export, list, remove, and update environments that have different versions of Python and/or packages installed in them.

You can create a conda environment for this workshop using the provided .yml file. The python version and all needed packages are listed in the environment.yml file.

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
% conda env create --file environment.yml
% conda activate cic-workshop
```
Note, you will need conda version 4.6 and later. If you need to update your version use `conda update conda`.

**Using Anaconda Navigator**

To use the Anaconda Navigator GUI, check the step by step guide at the end of the [google slides](https://tinyurl.com/resbaz2022python) accompanying this workshop.

## Further Reading

- Using Anaconda for package management ([cheatsheet](https://docs.conda.io/projects/conda/en/latest/_downloads/843d9e0198f2a193a3484886fa28163c/conda-cheatsheet.pdf)) and [setting up environments](https://medium.com/datareply/working-with-python-environments-anaconda-package-manager-and-ides-663e771b6ed8)
- [Python](https://www.python.org/), and
- [Jupyter Notebooks](http://jupyter.org/)
