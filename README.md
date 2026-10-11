# House Price Prediction

A beginner machine learning project that predicts median housing values in California using regression models.

## Project Overview

The goal of this project is to train and evaluate machine learning models using housing and demographic data.

## Dataset

* **Source:** California Housing dataset from Scikit-learn
* **Samples:** 20,640
* **Input features:** 8
* **Target:** `MedHouseVal` (median house value in units of $100,000)

## Models

* Linear Regression
* Random Forest Regressor

## Results

| Model             |    MAE |   RMSE | R² Score |
| ----------------- | -----: | -----: | -------: |
| Linear Regression | 0.5332 | 0.7456 |   0.5758 |
| Random Forest     | 0.3275 | 0.5053 |   0.8051 |

Random Forest performed better across all three evaluation metrics on the test set.

## Key Finding

`MedInc` (median income) was the most important feature according to the Random Forest model's feature importance scores.

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Limitations

The dataset represents median housing values for geographic areas, not individual property sale prices. The target values are capped at 5.0 (equivalent to $500,000), which limits interpretation for higher-value areas.

## Future Improvements

* Tune model hyperparameters.
* Investigate prediction errors.
* Compare additional regression models.

## Project Status

Completed as a learning project. Further improvements are possible.

