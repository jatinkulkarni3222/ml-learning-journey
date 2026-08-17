KNN Classifier – Breast Cancer Prediction
📌 Overview

This project implements a K-Nearest Neighbors (KNN) Classification model to predict whether a breast tumor is Malignant (M) or Benign (B) using the Breast Cancer Wisconsin dataset.

KNN is a supervised machine learning algorithm that classifies a data point based on the classes of its nearest neighbors.

📊 Dataset

The dataset contains 569 observations and 30 numerical features describing characteristics of cell nuclei.

Target
M → Malignant
B → Benign

The id column was removed because it does not provide useful information for prediction.

⚙️ Machine Learning Workflow
Load the dataset
Perform basic data inspection
Remove unnecessary columns
Separate features (X) and target (y)
Encode the target variable
Split data into training and testing sets
Apply Feature Scaling
Train the KNN Classifier
Make predictions
Evaluate model performance
🧠 Why Feature Scaling?

KNN calculates the distance between data points. Since the dataset contains features with very different ranges, scaling is necessary so that larger-valued features do not dominate the distance calculation.

StandardScaler is used to standardize the features.

🛠️ Technologies Used
Python
NumPy
Pandas
Matplotlib
Scikit-learn
Jupyter Notebook
📈 Model Evaluation

The model is evaluated using:

Accuracy
Confusion Matrix
Classification Report

Different values of K can also be tested to understand how K affects model performance.

🎯 Key Learning

Through this project, I learned:

How KNN classification works
Why feature scaling is important for distance-based algorithms
How to train and evaluate a KNN model
How changing the value of K affects predictions
🚀 Future Improvements
Tune the optimal value of K
Compare KNN with Logistic Regression and Decision Tree
Perform cross-validation
Compare different scaling techniques
