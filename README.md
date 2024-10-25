Random Forest Classifier Model Evaluation
This project uses a RandomForestClassifier to classify data and evaluate model performance on both training and testing datasets. The code trains the model, makes predictions, and computes several metrics to assess accuracy and overall effectiveness.

Project Overview
The main objective is to:

Train a Random Forest Classifier on a given dataset.
Evaluate the model's performance by calculating metrics such as accuracy, F1 score, and precision on both training and testing sets.
Provide a detailed classification report for each dataset to understand performance per class.
Key Features
Model Training: The classifier is trained using the training dataset.
Performance Metrics: Calculated metrics include:
Accuracy
F1 Score
Precision
Classification Report for both training and testing sets
Code Structure
The code defines a RandomForestClassifier model and includes a loop for easy extension to add additional models if needed. Key parts of the evaluation include:

Model Training: The model is trained on X_train and Y_train.
Predictions: Predictions are made on both the training and test sets.
Metric Calculation:
The metrics are computed and displayed in a well-formatted structure, each to four decimal points for consistency.
