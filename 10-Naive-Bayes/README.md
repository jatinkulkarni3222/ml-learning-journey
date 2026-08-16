# Naive Bayes

This folder contains my learning and implementation of the **Naive Bayes classification algorithm**, with a focus on understanding the underlying probability concepts and applying them to a simple classification problem.

## Topics Covered

- Bayes' Theorem
- Conditional Probability
- Naive Bayes assumption
- Prior probability
- Likelihood
- Posterior probability
- Classification using Naive Bayes
- Categorical feature handling
- Model implementation using Scikit-learn
- Model prediction and evaluation

## Dataset

The project uses the **Play Tennis dataset**, a small categorical dataset commonly used to understand Naive Bayes classification.

The objective is to predict whether a person will **Play Tennis** based on features such as:

- Outlook
- Temperature
- Humidity
- Wind

## Implementation

The notebook `naiveBayes.ipynb` covers:

1. Loading and exploring the dataset
2. Understanding the probability calculations behind Naive Bayes
3. Preparing categorical features
4. Training a Naive Bayes classifier
5. Making predictions
6. Evaluating the model

## Key Concept

Naive Bayes uses Bayes' theorem to calculate the probability of a class given the observed features.

The **"naive" assumption** is that the features are conditionally independent of each other given the class.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Purpose

The goal of this notebook is to build an intuitive understanding of **Naive Bayes** by connecting probability concepts with a practical machine learning classification problem.
