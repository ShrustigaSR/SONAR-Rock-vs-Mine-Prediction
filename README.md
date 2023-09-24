# SONAR-Rock-vs-Mine-Prediction

## Project Overview

This project is focused on developing a machine learning model to classify sonar signals as either rocks or mines. Sonar signals can be used for various applications, and in this case, we aim to distinguish underwater objects as rocks or mines.

## Data

The dataset used for this project contains a collection of sonar signals and their corresponding labels. Each data point represents a sonar signal, and the label indicates whether it's a rock (R) or a mine (M).

**Data Attributes:**
- Feature1, Feature2, ..., Feature60: Numerical features extracted from sonar signals.
- Label (Target Variable): R (Rock) or M (Mine)

The dataset is available as a CSV file (or in another suitable format).

## Dependencies

Before running the project, make sure you have the following dependencies installed:

- Python (3.7 or later)
- NumPy
- Pandas
- scikit-learn (sklearn)

You can install these libraries using pip:

```bash
pip install numpy pandas scikit-learn
```

## Results

The project evaluates the logistic regression model's performance in classifying sonar signals into rocks and mines. The primary metric used for evaluation is accuracy.
:



