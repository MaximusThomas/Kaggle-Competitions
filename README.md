# Titanic Survival Prediction

A machine learning project predicting passenger survival on the Titanic using the famous Kaggle dataset.

## Overview

This project implements multiple classification models to predict whether passengers survived the Titanic disaster based on various features such as passenger class, age, sex, family size, and fare.

## Models Implemented

- **Logistic Regression**: 79.9% accuracy
- **Gradient Boosting Classifier**: 81.6% accuracy
- **Random Forest Classifier**: 81.6% accuracy

## Features Used

- Pclass (Passenger class)
- Sex
- Age
- Fare
- Family Size (SibSp + Parch)
- Alone (boolean indicating if passenger traveled alone)

## Data Preprocessing

- Filled missing Age values with median
- Created Family Size feature from SibSp and Parch
- Created Alone feature
- Encoded Sex as binary variable
- Filled missing Fare values with median

## Results

Final model (Gradient Boosting Classifier) achieved 81.6% accuracy on the validation set.

## Files

- `titanic.ipynb`: Main analysis and modeling notebook
- `train.csv`: Training dataset
- `test.csv`: Test dataset
- `submission.csv`: Final predictions

## Requirements

- pandas
- scikit-learn
- matplotlib
- jupyter

## Usage

1. Install required packages: `pip install pandas scikit-learn matplotlib jupyter`
2. Open `titanic.ipynb` in Jupyter Notebook
3. Run all cells to reproduce the analysis

## Author

[Your Name]

## License

This project is for educational purposes.
