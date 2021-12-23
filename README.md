Demo homework for RS School Machine Learning course.

This demo uses [Heart Disease UCI](https://www.kaggle.com/ronitf/heart-disease-uci) dataset.

# Usage
This package allows you to train model for detecting the presence of heart disease in the patient.
1. Clone this repository to your machine.
2. Download Heart Disease UCI dataset, save csv locally (default path is *data/heart.csv* in repository's root).
3. Make sure Python 3.9 and [Poetry](https://python-poetry.org/docs/) are installed on your machine (I use Poetry 1.1.11).
4. Install the project dependencies:
```sh
poetry install --no-dev
```
5. Run train with the following command:
```sh
poetry run train -d <path to csv with data> -s <path to save trained model>
```
You can configure additional options in the CLI. To get a full list of them, use help:
```sh
poetry run train --help
```
