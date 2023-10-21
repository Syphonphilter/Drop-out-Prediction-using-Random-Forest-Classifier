Student Dropout and Academic Success Prediction
Overview
This project aims to predict students' dropout and academic success using machine learning techniques. It leverages various input features to build predictive models.

# Table of Contents
Project Description
Data
Getting Started
Usage
Results
Contributing
License
Project Description
In this project, we seek to tackle the important problem of predicting students' academic success and identifying potential dropouts. By employing machine learning algorithms, we can analyze various input features, including demographic information, academic history, and more, to make predictions.

Data
# Example Data Sources
Data source gotten from https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success
Data Preprocessing
Data was pre processed using Pandas.
Machine Learning Models
skitlearn and Synthetic Minority Oversampling Technique were used

Getting Started
# Prerequisites:
Python3 jupyter Notebook
bash
Copy code
# Example installation instructions
pip install -r requirements.txt
# Usage Jupyter Notebook
Execute this to select your desired classifier
```
SelectedClassifier = input("Select your classifier, KNN-Classifier, RandomForest, Logistic-Regression, and Decision-Tree")
print(SelectedClassifier)
```
# Example usage in .py 
python3 Dropout_Classification_ML_Project.py
# Results
Random forest classiifer outperforms becasue of its ability to prune and its Ensemble Method.
# Contributing
Please feel free to contribute by making pull requests.
Include guidelines for reporting issues and submitting pull requests.
# License MIT
Specify the project's license and any terms of use.