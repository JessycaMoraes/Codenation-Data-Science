# Discover the best math scores in ENEM 2016

You will need to create a model to predict the math test score of those who participated in ENEM 2016. To do this, you will use Python, Pandas, Sklearn and Regression.

## Topics

In this challenge you will learn:

- Python
- Pandas
- Sklearn
- Regression

## Requirements

You will need Python 3.6 (or higher) and the pip package manager.

It is recommended that you use a [ambiente virtual](https://pythonacademy.com.br/blog/python-e-virtualenv-como-programar-em-ambientes-virtuais). To do this, run the commands as in the example below:

Linux/macos

    pip3 install virtualenv
    virtualenv ../venv -p python3
    source ../venv/bin/activate 
    pip install -r requirements.txt

Windows

    pip3 install virtualenv
    virtualenv ..\venv -p python3
    ..\venv\Scripts\activate
    pip install -r requirements.txt


When you finish the challenge, you can exit the created environment with the `deactivate` command

## Details

The context of the challenge revolves around the results of ENEM 2016 (available in the file train.csv). This file, and only this file, should be used for all challenges. If you have any questions about the columns, consult the [Enem 2016 Microdata Dictionary](https://s3-us-west-1.amazonaws.com/acceleration-assets-highway/data-science/dicionario-de-dados.zip).

In the test.csv file, create a model to predict the math test score (column `NU_NOTA_MT`) of those who participated in the ENEM 2016.

Save your answer in a file called answer.csv with two columns: `NU_INSCRICAO` and `NU_NOTA_MT`.

