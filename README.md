# UBC-EL-ML
This repository includes my Final Project, for "Introduction to Machine Learning" course in the UBC Extended Learning - Key Capabilities for Data Science program, in both HTML and Jupyter Notebook versions. 

## Project Summary
For this project, I was given the data set *cheese_data.csv*, which contains relevant information of over 1,000 cheese products, and tasked with building a machine learning model with Python programming language via Jupyter Notebook. The goal I proposed for the machine learning model is to **predict the fat level, high or low, in cheese, as well as testing which type of ML model would work best under different scoring metrics, such as "accuracy", "recall", "percision", and "f1 score".** This project utilized mostly *classification models* instead of regression models, as those models can generate better the predictions I wished the ML model to make; in addition, different models were imported and tested, such as **DummyClassifier**, **KNeighborsClassifier**, and **RandomForestClassifier**. 

The final ML model that works best is a **RandomForestClassifier with a balanced class weight**; after putting the model through **RandomSearchCV** and a confusion matrix, the classification report indicated a lack of underfitting nor overfitting, thus making it the best model to predict the fat level in the *cheese_data.csv*.

For more information, please download and open the HTML or Jupyter Notebook file (HTML might be easier should you not have Anaconda or Jupyter Notebook installed).
