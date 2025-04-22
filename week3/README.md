# Getting to know our customer base better: which state has the customers with the best credit scores?

## Objective

We want to get to know our customers better by state. To do this, we start an analysis of their credit scores.
To perform the initial check, we need some values.
The values ​​are the mean, median, mode and standard deviation of the credit score.

## Topics

In this challenge you will learn:

- Mean;
- Median;
- Mode;
- Standard deviation.

## Requirements

You will need Python 3.6 (or higher).

It is recommended that you use a [virtual environment](https://pythonacademy.com.br/blog/python-e-virtualenv-como-programar-em-ambientes-virtuais). To do this, run the commands as in the example below:

    pip3 install virtualenv
    virtualenv venv -p python3
    source venv/bin/activate 

When you finish the challenge, you can exit the environment created with the `deactivate` command

## Details

The response must contain the values ​​of the mean, median, mode and standard deviation of the credit score for each state in the dataset.
The submission file must be in json format, as per the example file "submission.json".

**NOTE:** It is recommended to use Python and pandas for this challenge, but it is also possible to use other tools and programming languages.

Data description:
'id': Customer identifier
'sobrenome': Customer's last name
'pontuacao_credito': Customer's credit score (the higher, the better the customer generally)
'estado_residencia': Customer's state of residence
'genero': Customer's gender
'nivel_estabilidade': Customer's stability level
'saldo_conta': Available balance in the customer's account
'numero_produtos': Number of products the customer consumes
'possui_cartao_de_credito': Has a registered credit card
'membro_ativo': Member accesses and consumes frequently

Note: The data is fictitious, but it attempts to represent the reality of a customer base of a SaaS product.