# Jupyter Notebooks: ttest.ipynb and regression.ipynb

This repository contains two Jupyter Notebook examples that demonstrate statistical analysis using t-tests and linear regression.

## Table of Contents

1. [Overview](#overview)
2. [Installation](#installation)
3. [Running the Notebooks](#running-the-notebooks)
4. [Notebook Descriptions](#notebook-descriptions)
5. [References](#references)

## Overview

These Jupyter Notebooks showcase how to perform statistical analysis using Jupyter, Python, and popular data science libraries. The `ttest.ipynb` notebook demonstrates how to conduct a t-test for comparing two sample means, while the `regression.ipynb` notebook covers linear regression analysis.

## Installation

To run these Jupyter Notebooks, you'll need to have Jupyter installed on your system. If you haven't already installed it, follow these steps:

1. Install Python (if not already installed). You can download Python from [python.org](https://www.python.org/downloads/).

2. Install Jupyter using pip, a package installer for Python. Open your terminal (or command prompt) and run the following command:
   
   ```bash
   pip install jupyter
   ```
3. if you want to run on a virtual environment  
     - Create and activate a virtual environment  
     ```
     python -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate  
    ```
    - Install the project dependencies from requirements.txt  
    ```
    pip install -r requirements.txt  
    ```
    
## Running the Notebooks
Once you have Jupyter installed, follow these steps to run the notebooks:  

Clone or download this repository to your local machine.  

Open a terminal (or command prompt) and navigate to the directory where you saved the notebooks.  

Launch Jupyter Notebook by running the following command:  
```
jupyter notebook
```
Your web browser will open, displaying the Jupyter Notebook dashboard. Click on the notebook you want to open (ttest.ipynb or regression.ipynb) to start working with it.

## Notebook Descriptions
#### ttest.ipynb
This notebook demonstrates how to perform a t-test for comparing two sample means. It includes explanations of the t-test concept, assumptions, and step-by-step implementation using random generarated data from Python and libraries such as NumPy and SciPy. I alson demonstrate how to investigate a sample of data from patients, of different ages and sex, of their blood pressure before and after they had recieved treatment using the ttest.

#### regression.ipynb
In this notebook, you'll learn about linear regression analysis. It covers the basics of linear regression, how to fit a linear regression model to data, and how to interpret the results. Python libraries such as NumPy, pandas, and scikit-learn are used for this analysis.

# Other Files in the Repo

#### requirements.txt

The requirements.txt file is used to specify the external libraries and dependencies that the Python project requires to run properly. This file is often used in conjunction with package management tools like pip to ensure that the correct versions of these dependencies are installed. Each line in the requirements.txt file typically follows the format *package-name==version*, where *package-name* is the name of the Python package or library and *version* is the specific version used when creating this notebook.

The requirements.txt file lists the required packages and their specified versions. For instance, it states that the project requires:

Matplotlib version 3.5.1  
NumPy version 1.23.0  
Pandas version 1.4.2  
SciPy version 1.7.3  
Seaborn version 0.11.2  
Statsmodels version 0.13.2  
Scikit-learn version 1.0.2  
IPython version 7.27.0  
IPywidgets version 7.6.5  
    
#### .gitignore

The .gitignore file is used to specify files and directories that should be ignored by version control systems like Git. When developing a project, there are often files and directories that are generated during development or contain sensitive information that you don't want to include in your version control repository. Adding them to the .gitignore file ensures that they are not tracked or shared through the repository.
 
## References
Here are some resources that provide further information on the topics covered in these notebooks:

[Jupyter Documentation](https://docs.jupyter.org/en/latest/)  
[NumPy Documentation](https://numpy.org/doc/)  
[SciPy Documentation](https://docs.scipy.org/doc//scipy/index.html)  
[pandas Documentation](https://pandas.pydata.org/docs/)  
[scikit-learn Documentation](https://scikit-learn.org/stable/index.html)   
Feel free to explore, modify, and use these notebooks as a starting point for your own data analysis projects!