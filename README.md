# ds-project-1: EDA with King County Housing Data

First individual project at the __neuefische_ bootscamp performing EDA.

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

One of the first steps when starting any data science project is to create a virtual environment. For this project you have to create this environment from scratch yourself. However, you should be already familiar with the commands you will need to do so. The general workflow consists of... 

* setting the python version locally to 3.9.8
* creating a virtual environment using the `venv` module
* activating your newly created environment 
* upgrading `pip` (This step is not absolutely necessary, but will save you trouble when installing some packages.)
* installing the required packages via `pip`

At the end, you want to make sure that people who are interested in your project can create an identical environment on their own computer in order to be able to run your code without running into errors. Therefore you can create a `requirements file` and add it to your repository. You can create such a file by running the following command: 

You can install the virtual environment and the required packages like this:

```sh
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip  
pip install -r requirements.txt
```

*Note: In rare case such a requirements file created with `pip freeze` might not ensure that another (especially M1 chip) user can install and execute it properly. This can happen if libraries need to be compiled (e.g. SciPy). Then it also depends on environment variables and the actual system libraries.*

### Unit testing (Optional)

If you write python scripts for your data processing methods, you can also write unit tests. In order to run the tests execute in terminal:

```bash
pytest
```

This command will execute all the functions in your project that start with the word **test**.
