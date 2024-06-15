# Iris Flower Classification
This project uses machine learning to classify Iris flowers into three species (Setosa, Versicolor, and Virginica) 
based on their features (sepal length, sepal width, petal length, and petal width). 
The project is implemented in Python using libraries such as scikit-learn, pandas, and matplotlib.
## Features
- Data preprocessing
- Exploratory data analysis
- Model training and evaluation
- Hyperparameter tuning
- Visualization of results
## Dataset
The Iris dataset is used for this project. 
It contains 150 samples of Iris flowers, with 50 samples from each of the three species. 
### Model
The project uses the K-Nearest Neighbors (KNN) algorithm to classify the Iris species. 
The optimal number of neighbors (k) is determined using cross-validation.
The dataset is available from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Iris).
## Results
The KNN model achieves an accuracy of approximately 96% on the test set. 
Classification Report:
              precision    recall  f1-score   support

      setosa       1.00      1.00      1.00        10
  versicolor       1.00      0.92      0.96        12
   virginica       0.92      1.00      0.96        12

    accuracy                           0.97        34
   macro avg       0.97      0.97      0.97        34
weighted avg       0.97      0.97      0.97        34



