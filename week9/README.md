# Find out who took the ENEM 2016 just for practice

In this challenge you must find out which students are taking the test just for practice.

## Topics

In this challenge you will learn:

- Python
- Pandas
- Sklearn
- Regression
- Classification

## Requirements

You will need Python 3.6 (or higher) and the pip package manager.

To install the requirements, run the command as in the example below:

    pip install -r requirements.txt

## Detalhes

The context of the challenge revolves around the ENEM 2016 results (available in the train.csv file). This file, and only this file, should be used for all challenges. If you have any questions about the columns, please consult the [Enem 2016 Microdata Dictionary](https://s3-us-west-1.amazonaws.com/acceleration-assets-highway/data-science/dicionario-de-dados.zip).

Some students decide to take the ENEM exam early, as a test (IN_TREINEIRO column). In this challenge, you must create a binary classification model to infer the same. The possible results of your answer must be “0” or “1”.

Save your answer in a file called answer.csv with two columns: `NU_INSCRICAO` and `IN_TREINEIRO`.