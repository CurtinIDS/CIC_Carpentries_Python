# Curtin Institute for Data Science - Introduction to Data Science using Python

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/CurtinIC/CIC_Carpentries_Python/master)


## Schedule

1. [Introduction to the Workshop and Tools](https://docs.google.com/presentation/d/1fLcE69MHGyxIe7hQbCRfwvFBdZb83kb4wilbCrWWq0w/edit?usp=sharing)
2. [Short Introduction to Programming in Python](https://datacarpentry.org/python-ecology-lesson/01-short-introduction-to-Python.html)
3. [Starting With Data](https://datacarpentry.org/python-ecology-lesson/02-starting-with-data.html)
4. [Indexing, Slicing and Subsetting DataFrames in Python](https://datacarpentry.org/python-ecology-lesson/03-index-slice-subset.html)
5. [Data Types and Formats](https://datacarpentry.org/python-ecology-lesson/04-data-types-and-format.html)
6. [Combining DataFrames with Pandas](https://datacarpentry.org/python-ecology-lesson/05-merging-data.html)
7. [Data Workflows and Automation](https://datacarpentry.org/python-ecology-lesson/06-loops-and-functions.html)
8. [Making Plots with plotnine](https://datacarpentry.org/python-ecology-lesson/07-visualization-ggplot-python.html)

## Installing Miniconda

### Windows
- Open https://docs.conda.io/projects/miniconda/en/latest/ with your web browser.
- Download Miniconda3 Windows 64-bit.
- Install by running the Miniconda Installer, using the recommended settings.
- After installing, open the "Anaconda Prompt (miniconda3)" program to use Miniconda 3.

## MacOS
- Open https://docs.conda.io/projects/miniconda/en/latest/ with your web browser.
- Download Miniconda3 macOS Apple M1 64-bit pkg.
- Install by running the Miniconda Installer, using the recommended settings.
- After installing, re-open Terminal to use Miniconda 3.

## Linux
- Open https://docs.conda.io/projects/miniconda/en/latest/ with your web browser.
- Download the relevant package for your specific flavour of Linux.
- Open a Terminal window and navigate to your download directory.
- Type
  ```
  bash Miniconda3-
  ```
- and then press **Tab** to autocomplete the full file name. The name of file you just downloaded should appear. Press Enter. 
- You will follow the text-only prompts. 
  - To move through the text, press **Spacebar**. 
  - Type yes and press enter to approve the license. 
  - Press **Enter** to approve the default location for the files. 
  - Type yes and press Enter to prepend Miniconda to your PATH (this makes the Miniconda distribution the default Python).
- After installing, re-open Terminal to use Miniconda 3.

## Creating a conda environment

Environments allow you to have multiple sets of Python packages installed at the same time, making reproducibility and upgrades easier. You can create, export, lis, remove and update environments that have different versions of Python and/or packages installed in them.

You can create a conda environment for this workshop using the supplied *environment.yml* file which specifies the Python version and required packages. 

1. On Windows, open "Anaconda Prompt (miniconda3) or if using Mac/Linux, open Terminal.
2. Navigate to this repository. For example, if you downloaded the CIC_Carpentries_Python respository in your Downloads directory, you could type the following.
    ```
    % cd Desktop
    % cd CIC_Carpentries_Python
    ```
3. To install the environment on any platform and activate the CIC_Carpentries_Python environment, type:
    ```
    % conda env create ---file environment.yml
    % conda activate cids-workshop
    ```
  
## Installing VS Code (Optional)
1. Open https://code.visualstudio.com/ with your web browser.
2. Download VS Code for your specific platform/Operating System.
3. Run the VS Code Installer.
4. Open VS Code and in the Extension sidebar and install the Python and Jupyter extensions.

## Further Reading

- Using Anaconda for package management ([cheatsheet](https://docs.conda.io/projects/conda/en/latest/_downloads/843d9e0198f2a193a3484886fa28163c/conda-cheatsheet.pdf)) and [setting up environments](https://medium.com/datareply/working-with-python-environments-anaconda-package-manager-and-ides-663e771b6ed8)
- [Python](https://www.python.org/)
- [Jupyter Notebooks](http://jupyter.org/)
- [Getting Started with Python in VS Code](https://code.visualstudio.com/docs/python/python-tutorial)
