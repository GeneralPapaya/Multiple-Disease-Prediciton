# Multiple Disease Prediction Analysis

This project explores the use of various machine learning classification algorithms to predict the onset of several chronic diseases. For each disease, multiple models are trained, evaluated, and compared to identify the most effective classifiers.

The analysis focuses on key machine learning steps, including data preprocessing, handling class imbalance using **SMOTE (Synthetic Minority Over-sampling Technique)**, and visualizing model performance with **ROC curves**.

-----

## Diseases Covered

This repository contains separate analyses for the following conditions:

  * **Liver Disease**
  * **Kidney Disease**
  * **Diabetes**
  * **Asthma**

-----

## Models & Techniques

A wide range of classification algorithms were used to find the best-performing model for each disease.

### Classification Algorithms

  * Logistic Regression
  * Random Forest
  * K-Nearest Neighbors (KNN)
  * Support Vector Classifier (SVC)
  * Decision Tree Classifier
  * AdaBoost Classifier
  * Multi-layer Perceptron (MLP)

### Performance Evaluation

Model performance is primarily evaluated using **Receiver Operating Characteristic (ROC) curves** and the **Area Under the Curve (AUC)** score, providing a clear visual comparison of how well each model distinguishes between classes.

-----

## Project Structure

The repository is organized by disease, with each Jupyter Notebook containing a complete, standalone analysis.

  * `liver.ipynb`: Contains the data preprocessing, model training, and evaluation for predicting **liver disease**.
  * `kd.ipynb`: Contains the analysis and model comparison for predicting chronic **kidney disease**.
  * `diabetes.ipynb`: Contains the analysis and model comparison for predicting **diabetes**.
  * `asthma.ipynb`: Contains the analysis and model comparison for predicting **asthma**.

-----
