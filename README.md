# KNN_irirs_classification
KNN (K-Nearest Neighbors) is a supervised machine learning algorithm used for classification and regression.
Iris Flower Classification using K-Nearest Neighbors (KNN)

Project Description

This project demonstrates how the K-Nearest Neighbors (KNN) machine learning algorithm is used to classify iris flowers into three species—Setosa, Versicolor, and Virginica—based on their sepal and petal measurements. The model is trained and tested using the famous Iris dataset available in scikit-learn.

Libraries Used
Library	Purpose
numpy	Numerical computations
pandas	Data handling and analysis
matplotlib	Data visualization
seaborn	Statistical plots
sklearn.datasets	Load Iris dataset
sklearn.model_selection	Train-test split
sklearn.neighbors	KNN classifier
sklearn.metrics	Model evaluation
Algorithm Used

K-Nearest Neighbors (KNN)
KNN classifies a data point based on the majority class of its K nearest neighbors using distance metrics such as Euclidean distance.

1. Importing Libraries
All required libraries are imported for data handling, visualization, model training, and evaluation.

2. Loading Dataset
The Iris dataset is loaded using load_iris() from sklearn.datasets.

3️. Data Preprocessing
Converted dataset into a Pandas DataFrame

Mapped numeric labels to species names

4️. Train-Test Split
Data is split into 80% training and 20% testing using train_test_split().

5️. KNN Model Creation
A KNN classifier is created with K = 5 neighbors.

6️. Model Training
The model is trained using the .fit() method.

7️. Prediction
The trained model predicts flower species for test data.

8️. Model Evaluation
Accuracy score
Classification report
Confusion matrix

9️. Visualization
A heatmap is plotted to visualize the confusion matrix.
