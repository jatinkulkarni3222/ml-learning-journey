# Support Vector Machine (SVM)

This folder covers the fundamentals and implementation of **Support Vector Machine (SVM)**, a supervised machine learning algorithm used primarily for classification.

## Topics Covered

* Support Vector Machine (SVM)
* Hyperplane and Decision Boundary
* Support Vectors
* Margin
* Hard Margin and Soft Margin
* `C` Parameter
* Kernel Functions
* Kernel Trick
* Linear Kernel
* Polynomial Kernel
* RBF Kernel
* SVM Classification

## Implementation

The concepts are implemented using **Python** and **Scikit-learn**. Synthetic datasets such as `make_circles()` are used to visualize decision boundaries and understand how different kernels handle non-linear data.

## Libraries

* NumPy
* Matplotlib
* Scikit-learn

## Files

| File                   | Description                                       |
| ---------------------- | ------------------------------------------------- |
| `SVMkernelTrick.ipynb` | SVM implementation and Kernel Trick visualization |

## Key Takeaway

SVM finds an optimal decision boundary by maximizing the margin between classes. The **Kernel Trick** enables SVM to solve non-linear classification problems by mapping data into a higher-dimensional feature space.
