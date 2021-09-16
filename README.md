# FMI in the Cloud

This repository contains the materials and instructions for the tutorial [FMI in the Cloud](https://2021.international.conference.modelica.org/vendor_tutorial.html) at the [14th International Modelica Conference 2021](https://2021.international.conference.modelica.org/).

## Prerequesites

- a [Google account](https://accounts.google.com/SignUp) to run the Python Notebook on [Google Colab](https://colab.research.google.com/)
- a clone or local copy of this repository
- a Conda environment with [FMPy](https://github.com/CATIA-Systems/FMPy) to run the Jupyter Notebook locally and to run the Web App
- a Python IDE or text editor to write the Web App

To create the Conda environment

- install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) (if you don't already have Conda installed)

- create a new Conda environment

```
conda create -c conda-forge -n fmi-tutorial python=3.9 fmpy
```

- activate the environment

```
conda activate fmi-tutorial
```

## Part 1: Create a Jupyter Notebook

`Option 1:` run the Jupyter Notebook on the cloud

- [open Heater.ipynb](https://colab.research.google.com/github/t-sommer/fmi-webapp-tutorial/blob/main/Heater.ipynb) on Google Colab

`Option 2:` run the Jupyter Notebook locally

- change into the directory where you downloaded or cloned this repository and run

```
jupyter Heater.ipynb
```

## Part 2: Create a Web App

## Part 3: Hackathon and Q&A

Build your own Jupyter Notebooks and Web Apps and ask any questions about FMPy.

or run 

```
jupyter 
## Installation

- Google Colab? https://mybinder.org/?
- docker?
- conda

## Jupyter Notebook

- cross-compile
- download / upload resources
- download results

## Build and deploy a WebApp

- setup enviroment
- flask basics
- UIs with Bootstrap
- control a simulation
- deployment

## Hackathon

- Build your own Jupyter Notebooks and web apps
