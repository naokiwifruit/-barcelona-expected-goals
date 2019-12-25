# Expected Goals (xG) for FC Barcelona
This repo is building as expected goals (xG) model for FC Barcelona from StatsBomb event data.
**NOTE**: This model is trained with shot data of only FC Barcelona bacause StatsBomb data is limited to the match Messi has played. Therefore this model should be utilized only for Barca's shot data Messi has played and does not have an generalization ability toward another data.

We attempt to implement [the paper by Müller-Budack et al](https://arxiv.org/abs/1910.00412) with Python.

## Dependency
Python 3.7.4

Python libraries:
- numpy 1.16.5
- pandas 0.25.1
- matplotlib 3.1.0
- seaborn 0.9.0
- scikit-learn 0.21.3
- category_encoders 2.1.0
- pyodbc 4.0.27
- tqdm 4.0.27
- statsbomb 0.3.0

## Setup
Install required Python libraries.
~~~
$ pip install -r ./requirements.txt
~~~

## Usage
Check jupyter notebooks.

## Articles
1. E. Müller-Budack et al, "'Does 4-4-2 exist?' -- An Analytics Approach to Understand and Classify Football Team Formations in Single Match Situations." [arXiv:1910.00412](https://arxiv.org/abs/1910.00412) (2019).