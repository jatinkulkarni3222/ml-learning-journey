
# Logistic Regression

This folder contains my implementation and learning notebooks for **Logistic Regression**, focusing on how classification works from the fundamentals.

## 📚 Notebooks

| Notebook                                                                                                                                     | Description                                                                                                                      |
| -------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| [perceptronTrick.ipynb](https://github.com/jatinkulkarni3222/ml-learning-journey/blob/main/08-Logistic-Regression/perceptronTrick.ipynb)     | Understanding the Perceptron Trick and how a linear decision boundary can be adjusted for classification.                        |
| [perceptronSigmoid.ipynb](https://github.com/jatinkulkarni3222/ml-learning-journey/blob/main/08-Logistic-Regression/perceptronSigmoid.ipynb) | Understanding how the sigmoid function converts the linear output into a probability and forms the basis of Logistic Regression. |

## 🧠 Concepts Covered

* Classification vs Regression
* Perceptron
* Perceptron Trick
* Decision Boundary
* Sigmoid Function
* Probability-based classification
* Logistic Regression intuition
* Linear combination of input features
* Converting model output into class predictions

## 🔄 Logistic Regression Intuition

Logistic Regression first calculates a linear combination of the input features:

```text
z = w₁x₁ + w₂x₂ + ... + b
```

The result is then passed through the **sigmoid function**, which converts it into a value between 0 and 1.

```text
        1
σ(z) = ─────────
       1 + e⁻ᶻ
```

This value can be interpreted as the probability of belonging to the positive class.

For example:

```text
Probability = 0.82 → Class 1
Probability = 0.21 → Class 0
```

## 🎯 Learning Goal

The goal of these notebooks is to understand **what happens inside Logistic Regression**, rather than treating it as just a ready-to-use machine learning algorithm.

---

### 📌 Part of My ML Learning Journey

This folder is part of my ongoing journey of learning **Machine Learning from fundamentals to implementation**.
