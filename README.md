# heart-disease

Heart Disease Prediction using Decision Tree (ID3 Algorithm)

This project implements a Heart Disease Prediction System using a Decision Tree model based on the ID3 (Iterative Dichotomiser 3) algorithm. The model is trained on a dataset (heart.csv) to classify whether a patient is likely to have heart disease.

# Project Overview
Built using Python and Scikit-learn
Uses entropy as the splitting criterion (ID3 concept)
Splits dataset into training and testing sets
Evaluates model performance using accuracy
Visualizes the decision tree

# Technologies Used
Python 
Pandas
Scikit-learn
Pydotplus
Graphviz
Dataset

File used: heart.csv
Contains medical attributes such as:
Age
Sex
Chest pain type
Blood pressure
Cholesterol
Maximum heart rate
And more...

Target column:
0 → No heart disease
1 → Heart disease present

# How It Works
Upload the dataset (heart.csv)
Load data using Pandas
Split into features (X) and target (y)
Apply train-test split (80% training, 20% testing)

Train Decision Tree using:

DecisionTreeClassifier(criterion='entropy')
Make predictions
Calculate accuracy
Generate and visualize the decision tree

# Output
Model Accuracy displayed in console

Decision Tree saved as:

id3_tree.png
# Example Result
Decision Tree (ID3-like) Accuracy: 0.85

(Accuracy may vary depending on dataset)

# Key Concepts
Decision Tree Classifier
ID3 Algorithm
Entropy & Information Gain
Machine Learning Classification

# Author

Alnafee Shaikh

