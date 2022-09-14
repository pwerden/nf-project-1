# ds-project-1: EDA with King County Housing Data

**First individual project at the _neuefische_ bootscamp performing EDA.**

The overall goal is to perform an Exploratory Data Analysis (EDA) of the King County Housing Data having in mind the requests of the stakeholder Nicole Johnson, buyer, who seeks for a "Lively, central neighborhood, middle price range, right timing (within a year)"

## Requirements

- pyenv
- python==3.9.8
- jupyterlab==3.2.6
- ipywidgets==7.6.5
- matplotlib==3.5.1
- pandas==1.3.5
- numpy==1.22.0
- jupyterlab-dash==0.1.0a3
- seaborn==0.11.1

## Setup

First of all, we want to create a new virtual environment with the most basic python modules. Therefore we are:

* setting the python version locally to 3.9.8
* creating a virtual environment using the `venv` module
* activating your newly created environment 
* upgrading `pip` (This step is not absolutely necessary, but will save you trouble when installing some packages.)
* installing the required packages via `pip`

The above modules are listed in a separate `requirements file`. Therefore, we just need to run the following command to set up the virtual environment and the required packages like this:

```sh
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip  
pip install -r requirements.txt
```