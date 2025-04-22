# Data Preprocessing in Python

In this challenge, we will practice data manipulation using the [pandas](https://pandas.pydata.org/) library. Data manipulation is one of the most fundamental tasks for a data scientist and pandas - Python's most popular library on the subject - helps make this task more enjoyable.

## Objective

The goal of this challenge is to extract some quantitative information that will help us understand the nature of the data at hand and gain some _insights_ into the _data set_.

To do this, we will use the [Black Friday](https://codenation-challenges.s3-us-west-1.amazonaws.com/data-science-0/black_friday.csv) _data set_ originally made available by [Analytics Vidhya](https://www.analyticsvidhya.com/) and publicly accessible through [Kaggle](https://www.kaggle.com). The dataset contains some variables related to commercial transactions carried out during Black Friday in a given retail store. Each observation is related to a specific item purchased by a user and a user may have purchased more than one item.

## Topics

In this challenge we will explore:

* Python
* Pandas
* Jupyter notebook

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
