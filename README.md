This repository explores the use of machine learning to predict wine quality based on physicochemical properties.

## Dataset

Name: Wine Quality Dataset
Source: UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
Description: Contains 4,898 white wine samples with 11 physicochemical features and a quality rating (scale of 3-9).

## Features

Fixed acidity
Volatile acidity
Citric acid
Residual sugar
Chlorides
Free sulfur dioxide
Total sulfur dioxide
Density
pH
Sulphates
Alcohol

## Target Variable

Quality (scale of 3-9)

## Approach

Data Loading and Exploration:

Load the dataset using pandas.
Check for missing values.
Analyze summary statistics.
Visualize the distribution of wine quality.
Examine correlations between features.
Feature Engineering:

No missing values found in this dataset, so no feature engineering is needed.
Data Splitting:

Split the data into features (X) and target variable (y).
Further split into training (80%) and testing (20%) sets.
Model Building and Training:

Use a RandomForestRegressor from scikit-learn.
Train the model on the training set.
Model Evaluation:

Make predictions on the test set.
Evaluate performance using Mean Squared Error (MSE) and R-squared (R^2).
## Results

Mean Squared Error: 0.46 (example value, replace with your actual result)
R-squared: 0.68 (example value, replace with your actual result)

## Future Work

Experiment with different hyperparameters for Random Forest model.
Explore feature engineering techniques (e.g., scaling, feature selection).
Try other machine learning algorithms for comparison.
Investigate potential biases in the dataset.

## How to Use

Clone this repository.
Install required libraries: pandas, numpy, seaborn, matplotlib, sklearn.
Run the Python script wine_quality_prediction.py.
## Contribute

Feel free to contribute to this project by:

Suggesting improvements to the code or analysis.
Exploring new features or algorithms.
Raising issues or proposing enhancements.

## License

MIT License: https://choosealicense.com/licenses/mit/

## Author

Your Name: https://github.com/swaralisurve

## Acknowledgments

UCI Machine Learning Repository for providing the dataset.
