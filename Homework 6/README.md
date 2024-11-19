# Homework 6: SVM Digit Classification

## Team Members

- **Jethro Libutan** - libutanj21@students.ecu.edu
- **Ben Casatelli** - casatellib20@students.ecu.edu

---

## Overview

In this project, we used SVM models to classify digits from the digits dataset. We compared three SVM kernels: linear, radial, and polynomial. To improve efficiency, we applied PCA to reduce the dimensionality of the dataset while retaining 80% of the original variance. Final model accuracy was evaluated using 5-fold cross-validation.

---

## Parameters Tuned

- **Linear Kernel**: `C`
- **Radial Kernel**: `C`, `gamma`
- **Polynomial Kernel**: `C`, `gamma`, `degree`, `coef0`

---

## Results (Table)

| Kernel         | Final 5-Fold CV Accuracy |
| -------------- | ------------------------ |
| **Linear**     | 0.9249                   |
| **Radial**     | 0.9711                   |
| **Polynomial** | 0.9638                   |

---

## Results (Detailed)

### Linear Kernel

- **Accuracy**: 0.9249
- **C**: 0.1505

### Radial Kernel

- **Accuracy**: 0.9711
- **C**: 4.4551
- **Gamma**: 0.0010

### Polynomial Kernel

- **Accuracy**: 0.9638
- **C**: 0.2847
- **Gamma**: 0.0033
- **Degree**: 2
- **Coef0**: 0.2739

---

## How to Run

1. Install Python libraries: `numpy`, `matplotlib`, `seaborn`, `scipy`, and `scikit-learn`.
2. Run the code in a Jupyter Notebook or Python script.
3. The output will display the best parameters and final 5-fold CV accuracies for each kernel.

---
