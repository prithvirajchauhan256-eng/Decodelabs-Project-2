

This project was developed as part of the DecodeLabs Artificial Intelligence Internship Program.

The objective of this project is to build a machine learning classification model capable of predicting whether a tumor is benign or malignant using the Breast Cancer Wisconsin Dataset. The project demonstrates the complete supervised learning workflow, including data loading, preprocessing, model training, testing, and performance evaluation.

Objectives

* Understand and explore a real-world dataset
* Split data into training and testing sets
* Train a machine learning classification model
* Evaluate model performance
* Generate predictions on unseen data

Technologies Used

* Python
* Scikit-learn
* Pandas

 Dataset

The project uses the Breast Cancer Wisconsin Dataset available in Scikit-learn.

Features

The dataset contains several medical measurements of tumors, including:

* Radius
* Texture
* Perimeter
* Area
* Smoothness
* Compactness
* Concavity
* Symmetry

 Target Classes

* Benign (Non-cancerous)
* Malignant (Cancerous)

Machine Learning Algorithm

 K-Nearest Neighbors (KNN)

KNN is a supervised learning algorithm that classifies data points based on the categories of their nearest neighbors.

 Project Workflow

1. Load the Breast Cancer Dataset
2. Separate features and target values
3. Split the dataset into training and testing sets
4. Train the KNN classification model
5. Make predictions on the testing dataset
6. Calculate model accuracy
7. Display sample predictions

 Results

The model achieved high classification accuracy on the testing dataset, demonstrating the effectiveness of KNN for medical data classification tasks.
 How to Run

Install Required Libraries

bash
py -m pip install scikit-learn pandas


### Run the Program

```bash
py project2.py
```

 Sample Output

text
Model Accuracy: 97.9%

Sample Predictions:
Actual: 1 Predicted: 1
Actual: 0 Predicted: 0

 Learning Outcomes

Through this project, I learned:

* Basics of supervised machine learning
* Data classification techniques
* Training and testing machine learning models
* Evaluating model performance using accuracy scores
* Working with real-world datasets in Python

Prithvi Raj

DecodeLabs Artificial Intelligence Internship 2026
