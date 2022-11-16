# Meat_Predictor
Assuming we are in a farming role we want to be able to predict the seasonality of chicken and potentially buy chicken futures when the prices are going to be the lowest. We also want to use both the Facebook Prophet time-series machine learning model and the XGBoost regression machine learning model to predict what the price will be in one year and three years.

## Technologies

Language: Python 3.7

Libraries used:

[Pandas](https://pandas.pydata.org/pandas-docs/stable/index.html) - For the creation and visualization of Data Frames

[Jupyter Labs](https://jupyter.org/) - An ipython kernel for interactive computing in python

[PyViz hvPlot](https://hvplot.holoviz.org/index.html) - A high level python library for interactive data visualization

[Scikit-Learn](https://scikit-learn.org/0.18/auto_examples/svm/plot_iris.html) - Powerful machine learning library

[Facebook Prophet](https://facebook.github.io/prophet/) - Industry gold standard for predicting time-series models

[XGBoost](https://xgboost.readthedocs.io/en/stable/) - Another industry standard machine learning tool similar to Random Forests 


## Installation Guide

If you are using an anaconda or a conda environment (which is highly recommended) chances are pandas, hvplot and jupyter labs are already installed in your virtual environment. In addition, installing Facebook's Prophet library will be necessary

For a full install activate a conda development environment and run in GitBash if not already installed, otherwise pip can be used:
```python
    conda install pandas
    conda install jupyterlab
    conda install -c pyviz hvplot
```

To install the other dependencies not included in the anaconda environment run:
```python
    conda install prophet
    conda install -c conda-forge py-xgboost 
    conda install -c intel scikit-learn
```

Check the to make sure everything has been installed properly
```python
    conda list pandas
    conda list hvplot
    conda list jupyter lab
    conda list prophet
    conda list xgboost
    conda list scikit-learn
```

## Usage

## Pros and Cons of Prophet Compared to XGBoost

## Summary of Predictions

## Collaborator Information

David Hutsell
> email: |
> [Git Hub]() |
> [LinkedIn]() 

Ryan Svendson
> email: rsvendson@gmail.com |
> [Git Hub]() |
> [LinkedIn]()

Saidee Padilla
> email: |
> [Git Hub]() |
> [LinkedIn]() 

Silvano Ross: 
> email: silvanoross3@gmail.com |
> [GitHub](https://github.com/silvanoross) |
> [LinkedIn](https://www.linkedin.com/in/silvano-ross-b6a15a93/)
