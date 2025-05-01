Implementation of Decision Trees and Random Forests
This repository provides implementations of Decision Trees and Random Forests for both classification and regression tasks. The code is written from scratch in Python (and optionally C), focusing on core algorithmic understanding and flexibility for educational or research purposes.
Features
Decision Tree Classifier and Regressor
Random Forest Classifier and Regressor (ensemble of decision trees)
Support for various impurity measures (Gini, Entropy)
Customizable hyperparameters (max depth, min samples split, max features, number of estimators)
Out-of-bag (OOB) error estimation for Random Forests
Example scripts for training, prediction, and evaluation
Comparison with scikit-learn implementations
Key Concepts
Decision Trees: Recursive partitioning of data based on feature splits that minimize impurity (e.g., Gini, entropy). Supports both classification and regression.

Random Forests: Ensemble of decision trees trained on bootstrapped samples and random feature subsets. Aggregates predictions (majority vote or averaging) for improved generalization and reduced overfitting.
OOB Error: Unbiased performance estimate using data not included in each tree's bootstrap sample.
Feature Importance: Relative contribution of each feature to model performance, available in Random Forests.
Customization
Adjust hyperparameters such as:
max_depth (tree depth)
min_samples_split (minimum samples to split a node)n_estimators (number of trees in forest)
max_features (fraction of features to consider at each split)
Easily extend code for new splitting criteria or additional functionality
