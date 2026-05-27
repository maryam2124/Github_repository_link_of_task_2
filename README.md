# Iris Flower Classification using Machine Learning

## Overview
This project implements a machine learning model to classify Iris flowers into different species based on their physical measurements.

The model is trained using the classic Iris dataset and demonstrates basic supervised learning classification.

---

## Dataset Overview

The dataset contains:
- Sepal length
- Sepal width
- Petal length
- Petal width
- Target species:
  - Setosa
  - Versicolor
  - Virginica

### Dataset Sample Image
![Iris Dataset](https://th.bing.com/th/id/R.e302368bb7ea31160f4f65c54005458f?rik=nthlZIivbefgYw&riu=http%3a%2f%2fsebastianraschka.com%2fimages%2fblog%2f2015%2fprincipal_component_analysis_files%2firis.png&ehk=cOg2sQskjZCmOgmDWIq7hbdNDFXn824OR00s7iy1%2fmU%3d&risl=&pid=ImgRaw&r=0)

---

## Objective
To build a classification model that:
- Loads Iris dataset
- Performs data preprocessing
- Trains a machine learning model
- Predicts flower species
- Evaluates accuracy

---

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Model Used
- Logistic Regression  

### Model Diagram / Workflow
![Iris Dataset](https://miro.medium.com/v2/resize:fit:460/1*cJpAE_emjoQl4Ug-M4EXTw.jpeg)

---

## Workflow

1. Load dataset
2. Explore data (EDA)
3. Split dataset into training and testing sets
4. Train classification model
5. Make predictions
6. Evaluate accuracy

---

## Model Performance

The trained model achieved strong performance on the Iris classification task.

- Mean Accuracy: **0.9733 (97.33%)**

This indicates that the model correctly classifies Iris flower species with high reliability using the selected features.

---

## Visualization Summary

The following visual analyses were performed to understand the dataset and model behavior:

### 1. Feature Distribution Analysis
We analyzed how sepal length, sepal width, petal length, and petal width vary across different Iris species. This helps in understanding class separability.

### 2. Scatter Plot Analysis
Pairwise feature relationships were visualized to observe clustering patterns between Setosa, Versicolor, and Virginica species.

### 3. Decision Boundary Insight
The model's classification behavior can be understood through decision regions formed in the feature space, showing how different species are separated.

### 4. Confusion Matrix Interpretation
The confusion matrix shows correct and incorrect predictions across classes, confirming that most predictions align with actual labels.

---

## Key Insight

The model performs well because the Iris dataset has clear feature separability, especially between Setosa and the other two classes. This makes it suitable for basic supervised classification tasks.
