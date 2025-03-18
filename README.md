Rock vs Mine Prediction Model

Overview

This project implements a classification model to predict whether an object detected by sonar is a rock or a mine. The model is built using Logistic Regression and trained on the Sonar dataset.

Dataset

The dataset used for this project is the Sonar Mines vs Rocks dataset, which is available from the UCI Machine Learning Repository. It consists of 208 samples, each having 60 numerical features representing frequency-based sonar readings.

Data Preprocessing

Loading the Dataset: The dataset is loaded into a Pandas DataFrame.

Handling Missing Values: The dataset does not have missing values, so no imputation is needed.

Label Encoding: The target labels ('M' for mines and 'R' for rocks) are encoded into binary values (1 for Mine, 0 for Rock).

Feature Scaling: Normalization or standardization is applied to ensure that all features have similar scales, improving model performance.

Train-Test Split: The dataset is split into training and testing sets, typically in an 80-20 ratio.

Model Selection & Training

The model used is Logistic Regression, which is a simple yet effective binary classification algorithm.

Steps:

Model Initialization: The Logistic Regression model is initialized using the sklearn.linear_model.LogisticRegression class.

Training: The model is trained using the training dataset.

Evaluation: Model performance is evaluated using metrics like accuracy, precision, recall, and F1-score.

Evaluation Metrics

The performance of the model is assessed using:

Accuracy Score

Confusion Matrix

Precision, Recall, and F1-Score

Results

The Logistic Regression model provides a reasonable classification accuracy on the test set, making it a suitable choice for predicting sonar-based objects.
