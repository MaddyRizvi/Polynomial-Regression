# Polynomial Regression

## Overview
This repository compares **Linear Regression** and **Polynomial Regression** to predict salaries based on position levels. The goal is to demonstrate why **Polynomial Regression** provides a better fit for non-linear data compared to **Linear Regression**. 

Note: This project can be used for any Dataset containing other number of independent variables.

## Dataset
The dataset used in this project is `Position_Salaries.csv` and contains the following columns:
- **Position Level**: The level of the position in the company (e.g., Level 1 to Level 10).
- **Salary**: The salary associated with each position level.

## Why Polynomial Regression?
Linear Regression fits a straight line to the data, which might not always capture the complexity of the underlying relationship. In this case, the relationship between position level and salary is non-linear, which is better captured by Polynomial Regression.

Polynomial Regression uses higher-degree polynomials to model the non-linear relationships, providing a better fit and more accurate predictions.

## Requirements
To run the code, you need the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `sklearn`

You can install the required libraries using:

```bash
pip install -r requirements.txt
```

# Usage

## Clone this repository to your local machine:

```bash
git clone https://github.com/YOUR_USERNAME/Polynomial-Regression.git
cd Polynomial-Regression
```
## Run the Python script to perform both Linear Regression and Polynomial Regression and visualize the results:

python polynomial_regression.py

## 3: The script will generate the following results:

A plot showing the Linear Regression model.

A plot showing the Polynomial Regression model.

A more detailed plot using a finer grid to show the Polynomial Regression fit in detail.

## Visual Results

### 1. Linear Regression Model
![Image](https://github.com/user-attachments/assets/dc801c3e-2fb7-4b56-93f4-180643ea5540)

This plot shows how **Linear Regression** fits the dataset. Notice that it does not accurately capture the curve in the data.

### 2. Polynomial Regression Model
![Image](https://github.com/user-attachments/assets/979d6bd2-6fe0-4949-88b1-48cb4ceb2432)

This plot demonstrates how **Polynomial Regression** provides a much better fit to the data by capturing the non-linear relationship between position level and salary.

### 3. Polynomial Regression with Smoother Curve
![Polynomial Smoother](https://github.com/user-attachments/assets/ae9a1f0b-fd68-4bc1-9b49-895ebe1eee6d)


This plot shows the prediction using a finer grid for the position level, which creates a smoother curve.


