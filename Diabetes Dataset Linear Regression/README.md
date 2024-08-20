# Diabetes Dataset Linear Regression

This project demonstrates the use of linear regression on the diabetes dataset provided by the `sklearn` library. The goal is to predict the progression of diabetes using various features of the dataset.

## Dataset

The diabetes dataset contains data for 442 patients, each represented by 10 features and a target value indicating disease progression.

## Features

- `age`: Age of the patient
- `sex`: Gender of the patient
- `bmi`: Body mass index
- `bp`: Average blood pressure
- `s1`-`s6`: Six blood serum measurements

## Requirements

- Python 3.x
- numpy
- matplotlib
- scikit-learn

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/diabetes-linear-regression.git
    ```

2. Navigate to the project directory:

    ```bash
    cd diabetes-linear-regression
    ```

3. Install the required packages:

    ```bash
    pip install numpy matplotlib scikit-learn
    ```

## Usage

1. Run the Python script:

    ```bash
    python diabetes_regression.py
    ```

2. The script will output the mean squared error (MSE), weights, and intercept of the linear regression model. It will also display a plot comparing the actual and predicted values for one of the features.

## Output

- **Mean Squared Error**: A measure of the model's accuracy. Lower values indicate better performance.
- **Weights**: Coefficients assigned to each feature by the model.
- **Intercept**: The value at which the regression line crosses the y-axis.

## Plot

The script generates a scatter plot showing the actual target values and a line representing the predicted values based on the first feature of the dataset.

## Acknowledgments

- The dataset used in this project is sourced from the `sklearn` library.
- Special thanks to the developers of numpy, matplotlib, and scikit-learn for providing the tools used in this project.
