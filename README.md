# Machine Learning Algorithms Practice

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![NumPy](https://img.shields.io/badge/NumPy-Used-orange?logo=numpy)
![Pandas](https://img.shields.io/badge/Pandas-Used-purple?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow?logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red?logo=jupyter)

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Core-blue)
![Reinforcement Learning](https://img.shields.io/badge/Reinforcement%20Learning-Added-success)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

A hands-on collection of **Machine Learning algorithms implemented and practiced while learning ML fundamentals**.

This repository focuses on understanding the **core concepts of machine learning algorithms** through experimentation, notebook implementations, and scratch implementations.

Some algorithms are implemented using **Scikit-learn**, while others are implemented **from scratch** to understand the internal mechanics of the models.

---

# Repository Overview

This repository contains implementations of **Supervised Learning**, **Unsupervised Learning**, and **Reinforcement Learning** algorithms commonly used in Machine Learning.

```
machine_learning_algorithms
│
├── supervised_learning
│   ├── Linear_regression
│   ├── logistic_regression
│   ├── KNN
│   ├── Decision_tree
│   ├── SVM
│   ├── Bagging(Random_Forest)
│   ├── Boosting
│   └── lasso-ridge-regression
│
├── unsupervised_learning
│   ├── Kmeans_clustering
│   ├── hierarchical_clustering
│   ├── DBSCAN
│   ├── PCA
│   └── anomaly_detection
│
└── reinforcement_learning
    ├── Q_learning
    ├── SARSA
    ├── Flappy_Bird_AI
    └── other_experiments
```

---

# Supervised Learning

Supervised learning algorithms learn patterns from **labeled data**.

### Linear Regression

Used for predicting continuous numerical values.

Includes:

* Regression implementation
* Scratch implementation
* Regression evaluation metrics

---

### Logistic Regression

Used for **binary classification problems**.

Includes:

* Classification implementation
* Scratch implementation
* Classification evaluation metrics

---

### K-Nearest Neighbors (KNN)

A **distance-based classification algorithm**.

Includes:

* KNN implementation
* KNN from scratch
* Cross validation pipeline

---

### Decision Trees

Tree-based models used for both **classification and regression**.

Includes:

* Decision Tree Classifier
* Decision Tree Regressor

---

### Support Vector Machine (SVM)

A powerful algorithm used for both classification and regression tasks.

Includes:

* SVM Classification
* SVM Regression

---

### Ensemble Methods

Combining multiple models to improve performance.

#### Bagging / Random Forest

* Ensemble learning using bagging techniques

#### Boosting

* AdaBoost
* Gradient Boosting
* XGBoost
* Heterogeneous Ensemble

---

### Regularization

Techniques to prevent **overfitting**.

Includes:

* Ridge Regression
* Lasso Regression

---

# Unsupervised Learning

Unsupervised learning algorithms work with **unlabeled data** and discover hidden patterns.

### Clustering Algorithms

* K-Means Clustering
* Hierarchical Clustering
* DBSCAN

---

### Dimensionality Reduction

**Principal Component Analysis (PCA)**
Used to reduce feature dimensions while preserving important information.

---

### Anomaly Detection

Techniques used to detect **outliers or unusual data points** in datasets.

---

# Reinforcement Learning

Reinforcement Learning focuses on training agents to make decisions by interacting with an environment and learning from rewards and penalties.

This folder contains practical implementations and experiments to understand how agents learn optimal behavior over time.

### Algorithms Covered

* **Q-Learning**

  * Value-based learning algorithm
  * Uses Q-table to learn optimal actions
  * Focus on exploration vs exploitation

* **SARSA (State-Action-Reward-State-Action)**

  * On-policy learning algorithm
  * Updates values based on actions actually taken
  * More stable but sometimes slower than Q-learning

---

### Project: Flappy Bird AI

A practical implementation where a reinforcement learning agent learns to play the Flappy Bird game.

Includes:

* Environment interaction
* Reward-based learning
* State-action decision making
* Continuous improvement through episodes

---

### What I Learned

* Difference between **supervised vs reinforcement learning**
* How agents learn using **rewards and penalties**
* Concepts like:

  * Exploration vs Exploitation
  * Q-table updates
  * Policy learning
* Real-world simulation using a game environment

---

# Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Jupyter Notebook

---

# Purpose of This Repository

This repository is part of my **Machine Learning learning journey**, where I explore and practice different algorithms to understand:

* How machine learning models work
* When to use different algorithms
* The difference between classification, regression, and clustering models
* Practical implementation of ML techniques

---

# Author

**Sagar Jain**

Interested in:

* Machine Learning
* Artificial Intelligence
* Deep Learning
* Data Science
