# CS5691 - Pattern Recognition and Machine Learning

This repository contains course materials, assignments, and resources for the **CS5691 Pattern Recognition and Machine Learning** course at IIT Madras.

## 📚 Course Overview

This course covers fundamental concepts in pattern recognition and machine learning, including:
- Probability and Statistics
- Decision Theory and Bayes Classifiers
- Density Estimation (MLE and Bayesian Inference)
- Unsupervised Learning (Dimensionality Reduction, Clustering)
- Principal Component Analysis (PCA)
- Linear Regression
- Classification with Linear Models and Kernel Methods
- Support Vector Machines (SVMs)
- Artificial Neural Networks (ANNs)
- Ensemble Methods and Decision Trees

## 📁 Repository Structure

```
.
├── Assignment1/          # Bayesian Classifiers
├── Assignment2/          # PCA and Dimensionality Reduction
├── Assignment3/          # Polynomial Regression with Regularization
├── Lectures/             # Course lecture slides
├── Tutorial_Worksheets/  # Practice worksheets and solutions
└── Course handout (v1).pdf
```

## 📝 Assignments

### Assignment 1: Bayesian Classification
- Implements Bayesian classifiers using multivariate Gaussian density functions
- Covers 4 cases:
  - Case 1: Same covariance matrix for all classes
  - Case 2: Different covariance matrices across classes
  - Case 3: Naive Bayes with σ²I covariance (same for all classes)
  - Case 4: Naive Bayes with σ²I covariance (different across classes)
- Works with linearly and non-linearly separable datasets
- Uses Maximum Likelihood Estimation (MLE)

### Assignment 2: Principal Component Analysis
- Implements PCA from scratch for dimensionality reduction
- Analyzes variance explained by principal components
- Works with image datasets (8x8 pixel images)
- Explores word embeddings and data visualization

### Assignment 3: Polynomial Regression
- Implements polynomial regression with quadratic regularization
- Explores bias-variance tradeoff
- Uses regularization parameter λ for model complexity control

## 📖 Lectures

The `Lectures/` folder contains comprehensive lecture materials:

| Module | Topic |
|--------|-------|
| M0a | Background on Probability |
| M1 | Introduction to Pattern Recognition and Machine Learning |
| M2 | Decision Theory (incl. Bayes classifiers) |
| M3 | Density Estimation (MLE and Bayesian Inference) |
| M4 | Unsupervised ML Methods (Spectral Linear Algebra Applications) |
| M5 | Dimensionality Reduction using PCA |
| M6 | Linear Regression |
| M7 | Classification: Linear Models and Kernel Methods |
| M8 | Support Vector Machines (SVMs) |
| M9 | Artificial Neural Networks (ANNs) |
| M10 | Combined Models and Ensemble Methods |

Additional materials include:
- EM Algorithm for Mixture Density Estimation
- K-means Algorithm Variants using Probabilistic Perspective

## 📋 Tutorial Worksheets

Practice worksheets are provided for key topics:
- Probability Concepts
- Calculus, Optimization, and Linear Algebra
- Decision Theory and Bayes Classifiers
- PCA for Dimensionality Reduction
- Linear Regression
- Logistic Regression
- Support Vector Machines
- Spectral Clustering (with Jupyter notebook tutorials)

## 🛠️ Technologies Used

- **Python 3.x** - Primary programming language
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Scikit-learn** - Machine learning utilities (e.g., PolynomialFeatures)
- **Jupyter Notebooks** - Interactive coding environment
- **LaTeX** - Assignment documentation

## 📖 Reference

- "Pattern Classification" by Richard O. Duda, Peter E. Hart, and David G. Stork

## 🎓 Course Information

- **Course Code**: CS5691
- **Institution**: Indian Institute of Technology Madras (IIT Madras)

## 📄 License

This repository is for educational purposes as part of the CS5691 course at IIT Madras.