# Digital Chemistry: AI in Drug Discovery - Workshop
This repository contains the code and instructions for setting up for the AI in Drug Discovery workshop sessions.

## Contents
During the workshop, we will be using a framework for machine learning in drug discovery called [DeepChem](https://github.com/deepchem/deepchem). DeepChem is a Python library/toolchain that combines multiple machine learning algorithms, frameworks and datasets and provides a unified interface for training and evaluating models in drug discovery.

For each workshop session, we will be practically using DeepChem through a set of tutorial [Jupyter Notebooks](https://ipython.org/notebook.html) from the [DeepChem library](https://github.com/deepchem/deepchem/tree/master/examples/tutorials).

### Workshop 1: Introduction to DeepChem (10/02/2022) - Current

This workshop will introduce you to the basics of DeepChem and will allow you to familiarize yourself with the library.

1. [Basic tools of the deep life sciences](Workshop_1/The_Basic_Tools_of_the_Deep_Life_Sciences.ipynb)

    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deepchem/deepchem/blob/master/examples/tutorials/The_Basic_Tools_of_the_Deep_Life_Sciences.ipynb)

2. [Working with datasets](Workshop_1/Working_With_Datasets.ipynb)

    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deepchem/deepchem/blob/master/examples/tutorials/Working_With_Datasets.ipynb)

3. [An introduction to Moleculenet](Workshop_1/An_Introduction_To_MoleculeNet.ipynb)

    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deepchem/deepchem/blob/master/examples/tutorials/An_Introduction_To_MoleculeNet.ipynb)

4. [Molecular fingerprints](Workshop_1/Molecular_Fingerprints.ipynb)

    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deepchem/deepchem/blob/master/examples/tutorials/Molecular_Fingerprints.ipynb)

## Getting Started
In order to get started it is recommended you clone this repository locally, even if working in google colab. This will download the repository content to your local machine. to clone the repository locally, open a terminal (command prompt/powershell on windows) and type:

`git clone https://github.com/GouldGroup/aidd-workshops.git`

Before each workshop session, this repository will be updated with the new workshop content. To update you're local copy of the repository, open a terminal in the current directory (command prompt/powershell on windows) and type:

`git pull`

for each workshop session, you will find the relevant Jupyter Notebooks within the respective workshop directory in this repository (e.g. `Workshop_1/The_Basic_Tools_of_the_Deep_Life_Sciences.ipynb`). You will also find google colab links to the notebooks in the contents section of this readme. 

If you choose to work in colab (recommended), you can open the notebooks in colab by clicking on the links in the contents section of this readme. You will need to be signed in to your google account. Should you wish to work locally, follow the instructions in the [Setup](##Setup) section below.

## Setup
To setup the development environment for these workshops, you need to have some conda distribution installed. We will use [Miniconda](https://docs.conda.io/en/latest/miniconda.html) for this workshop.

### Install Miniconda
Download and install the relevant version of Miniconda for your operating system. (you are probably running a Windows 64-bit or MAC 64-bit system). If you are using an M1 mac it is still recommended to install the 64-bit version of Miniconda.

### Install Dependencies
To install the required dependencies for the workshop and create a development environment for DeepChem, open a terminal in the current directory (Anaconda Prompt on Windows) and type:

`conda env create -f environment.yml`

### Activate the Development Environment
you will then need to activate the newly created environment. To activate the environment type:

`conda activate deepchem`

you will now be able to run `Jupyter notebook` and open the notebooks in this repository!
