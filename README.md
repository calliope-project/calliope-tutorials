# calliope-tutorials

Authors: Bryn Pickering, Stefan Pfenninger

License: Apache 2.0

# About

Tutorials on how to build, run, and analyse a model with the Calliope framework. Sets of tutorials are given for each version of calliope, to avoid backwards-incompatibility, with the relevant requirements file given in each directory.

## Current tutorials

Below is a list of current tutorials in this repository, click on any of interest to view the notebooks.

### Latest

- [Urban scale with MILP functionality](http://nbviewer.jupyter.org/github/calliope-project/calliope-tutorials/blob/master/0.5.3/UrbanScale_MILP.ipynb)

- [National Scale](http://nbviewer.jupyter.org/github/calliope-project/calliope-tutorials/blob/master/0.5.3/NationalScale.ipynb)

### Previous versions

## Setup

In order to edit the notebooks, you will need to have operate on local versions of them. If you are unfamiliar with creating and using conda environments and/or Jupyter notebooks, then you can follow the instructions below.

### 1. Install the Anaconda Python distribution

Download the Anaconda Python distribution and run the downloaded installer:

https://www.anaconda.com/download/

Make sure you download the Python 3 version.

### 2. Create an environment

Download or clone this GitHub repository and navigate to the directory of the version of interest (e.g. 0.5.3). Once Anaconda is installed, create a new conda environment with the required packages, by running the following command in a terminal (Linux or macOS) or a command-line window (Windows), making sure you run this command inside the relevant version directory containing:

```bash
conda env create -f requirements.yml
```

### 3. Ensure that you can successfully run a Jupyter Notebook

If you are unfamiliar with the Jupyter Notebook, have a look at [this quick start guide](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/index.html), in particular the section on [running the notebook](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html).
