Gesture UI Project - README

Project Overview

This project focuses on training and evaluating different machine learning classification algorithms on a dataset related to human activity recognition using smartphones. The goal is to compare various models and determine the most suitable one for deployment. The dataset consists of readings from accelerometers and gyroscopes, captured from 30 volunteers performing different activities.

Dataset

The dataset used in this project is derived from the "Human Activity Recognition Using Smartphones" dataset available on the UCI Machine Learning Repository. The dataset includes:

Feature names: Stored in features.txt

Data: Stored in dataset.txt

Target labels: Stored in targets.txt

Conclusion

This project compared three classification models (Logistic Regression, Random Forest, and kNN) for activity recognition. The best-performing model was selected based on accuracy and cross-validation results. PCA was used to reduce dimensionality and improve computational efficiency.

How to Run the Project
Clone this repository
- git clone "https://github.com/Cathal-McHale/Gesture_UI_Project1/"

Install required dependencies:

- pip install numpy pandas matplotlib seaborn scikit-learn

Place features.txt, dataset.txt, and targets.txt in the project directory.

Run the Python script to train models and evaluate their performance.
