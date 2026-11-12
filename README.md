# Simple Linear Regression

Predicts salary from years of experience using a simple linear regression model built with scikit-learn.

## Dataset

`Salary_Data.csv` contains 30 rows with two columns:

| Column            | Description                 |
|-------------------|-----------------------------|
| `YearsExperience` | Years of work experience    |
| `Salary`          | Annual salary               |

## What the script does

1. Loads the dataset with pandas.
2. Splits it into a training set (2/3) and a test set (1/3).
3. Fits a `LinearRegression` model on the training set.
4. Predicts salaries for the test set.
5. Plots the regression line against the training data and the test data.

## Requirements

- Python 3
- numpy
- pandas
- matplotlib
- scikit-learn

Install them with:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## Usage

Run the script from inside the project folder so it can find the CSV:

```bash
python simple_linear_regression.py
```

Two charts will open: **Salary vs Experience (Training set)** and **Salary vs Experience (Test set)**. Red points are the actual salaries and the blue line is the model's prediction.
