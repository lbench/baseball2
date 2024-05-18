# Baseball Injuries Prediction (BIP)
This python project is an attempt at using pitch by pitch and injury data to predict baseball injuries.

## Installation and execution

After downloading the folder, use [Poetry](https://python-poetry.org/) to
install BIP dependencies. Running main.py will make the main csv used for the analysis. 
This csv is then further manipulated in the juypter notebooks. "make_numerical_columns.ipynb" makes
"numerical_columns.csv" which is the input data to the R program that analyzes the data.
All results can be viewed in "baseball_models.html".


To make the "integrated_data.csv" file that the juypter notebooks analyze, please run the following commands.
Running main.py will take around 30 minutes and running the juypter notebook "make_numerical_columns.ipynb"
takes around 30 minutes.
```bash
pip install poetry
poetry install
poetry run main.py
```

## Created by: 
Luke Baylon, William Bench, Praneeth Bhojanala