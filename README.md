# ds-project-1: EDA with King County Housing Data

**First individual project at the _neuefische Data Science_ bootscamp performing EDA.**

The overall goal is to perform an Exploratory Data Analysis (EDA) of the [King County Housing Data](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction) having in mind the requests of a hypothetical stakeholder named  Nicole Johnson, who seeks to buy a house for a "lively, central neighborhood, middle price range, right timing (within a year)". The walk through can be found in **EDA.ipynb**.

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

First of all, we want to create a new virtual environment with the most basic python modules. Therefore we are (either with 1 **or** 2):

### 1) pyenv

* setting the python version locally to 3.9.8
* creating a virtual environment using the `venv` module
* activating our newly created environment 
* upgrading `pip` (optional, but handsome)
* installing the required packages via `pip`

The above modules are listed in a separate `requirements file`. Therefore, we just need to run the following command to set up the virtual environment and the required packages like this:

```sh
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip  
pip install -r requirements.txt
```

### 2) anaconda

* upgrade the `conda` package manager to the latest version
* creating a virtual environment named **venv_nf-p1** with set python version
* activating our newly created environment
* installing the required packages via `conda` from channel conda-forge

```sh
conda update conda
conda create -n venv_nf-p1 python=3.9.8
conda activate venv_nf-p1
conda install -c conda-forge --file requirements.txt
```

## Data

The dataset for the population density for the notebook *zipcode_data_king_county.ipynb* is stored in the `data.zip` folder. To unzip the data folder directly in the terminal run

```sh
unzip data.zip
```

For the other datasets links are given within the notebooks.