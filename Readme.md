Wine Quality Prediction
This project aims to predict the quality of wine using a Random Forest Classifier based on various physicochemical properties. The dataset used in this project is from the Wine Quality Dataset.

Dataset
The dataset used in this project can be found at: [/kaggle/input/wine-quality-dataset/WineQT.csv](url)

Features:
fixed acidity
volatile acidity
citric acid
residual sugar
chlorides
free sulfur dioxide
total sulfur dioxide
density
pH
sulphates
alcohol
Target:
quality (Integer ranging from 3 to 9)
Steps
Data Preprocessing:

Removed irrelevant columns (Id).
Checked for null values.
Split the data into training and testing sets (80/20 split).
Exploratory Data Analysis:

Visualized the distribution of quality ratings.
Created correlation heatmaps to understand feature relationships.
Plotted joint grids for specific feature combinations like pH vs fixed acidity.
Model Training:

Used Random Forest Classifier with 100 estimators.
Trained the model on the training data.
Achieved an accuracy of 70.31% on the test set.
User Input:

Allows users to input the physicochemical properties of a wine sample and predicts the wine quality.