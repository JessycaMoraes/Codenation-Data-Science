# Dimensionality reduction and feature selection

In this challenge, we will practice dimensionality reduction with PCA and variable selection with RFE.

## Objective

The objective of this challenge is to explore how PCA works and how we can obtain lower-dimensional _data sets_ through it.

To do this, we will use the [FIFA 2019](https://www.kaggle.com/karangadiya/fifa19) _data set_, which originally contains 89 variables with various attributes of more than 18 thousand players from the FIFA 2019 game.

## Topics

In this challenge, we will explore:

* Dimensionality reduction
* PCA
* Variable selection
* RFE

## Requirements

You will need Python 3 and pip. It is highly recommended to use virtual environments with virtualenv and the `requirements.txt` file to install the challenge dependencies:

```bash
$ pip3 install virtualenv
$ virtualenv venv -p python3
$ source venv/bin/activate
$ pip install -r requirements.txt
```

Windows

```bash
> pip3 install virtualenv
> virtualenv ..\venv -p python3
> ..\venv\Scripts\activate
> pip install -r requirements.txt
```

When finished, you can deactivate the virtual environment from virtualenv with:

```bash
$ deactivate
```
