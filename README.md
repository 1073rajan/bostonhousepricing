# Boston House Price Prediction

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Overview
This project aims to predict house prices in Boston using various machine learning algorithms. The dataset used is the famous Boston Housing Dataset, which includes features like crime rate, number of rooms, and distance to employment centers.

## Dataset
The dataset contains 506 samples with 13 features each. The target variable is the median value of owner-occupied homes in $1000's. The features are:

1. CRIM: per capita crime rate by town
2. ZN: proportion of residential land zoned for lots over 25,000 sq. ft.
3. INDUS: proportion of non-retail business acres per town
4. CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
5. NOX: nitric oxides concentration (parts per 10 million)
6. RM: average number of rooms per dwelling
7. AGE: proportion of owner-occupied units built prior to 1940
8. DIS: weighted distances to five Boston employment centers
9. RAD: index of accessibility to radial highways
10. TAX: full-value property tax rate per $10,000
11. PTRATIO: pupil-teacher ratio by town
12. B: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town
13. LSTAT: % lower status of the population

## Installation
1. Clone the repository:
    ```bash
    https://github.com/1073rajan/bostonhousepricing.git
    ```
2. Create and activate a virtual environment:

    ```bash
    conda create -p venv python==3.7 -y
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. **Exploratory Data Analysis (EDA)**:
    - Navigate to the `notebooks` directory and open `eda.ipynb` to explore the dataset and visualize the features.
  
2. **Model Training**:
    - Run the `train_model.py` script to train the models:
    ```bash
    python train_model.py
    ```

3. **Prediction**:
    - Use the `predict.py` script to make predictions on new data:
    ```bash
    python predict.py --input data/new_data.csv --output data/predictions.csv
    ```

## Model
Various regression models are used in this project:
- Linear Regression
- Ridge Regression
- Lasso Regression

Each model is evaluated based on metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared score.

## Results
The performance of the models can be found in the `results` directory. The `model_comparison.csv` file contains the evaluation metrics for each model.

## Contributing
Contributions are welcome! Please create a pull request with a detailed description of the changes.


## Acknowledgements
- This project uses the [Boston Housing Dataset](Sk-Learn Dataset) from the SK-learn Machine Learning Repository.
- Special thanks to the [scikit-learn](https://scikit-learn.org/stable/) team for providing such an excellent library.




## Software And Tools Requirements

1. [Githubs Account](https://github.com)
2. [Vs Code IDE](https://code.visualstudio.com)
3. [HerokuAccount](https://heroku.com)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Standard-The-Command-Line)

## DEMO

 ```bash
 https://bostonhouseprice.pythonanywhere.com/
 ```
