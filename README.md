# Day-71-Introduction-to-Machine-Learning

## Overview
This repository marks **Day 71** of my **150 Days of Data & AI Journey**.

Today, I started my journey into **Machine Learning (ML)** — understanding the core concepts, types, and workflow that power modern intelligent systems.

---

##  What is Machine Learning?

Machine Learning is a subset of Artificial Intelligence that allows systems to **learn from data and improve automatically** without being explicitly programmed.

---

##  Types of Machine Learning

### 1️ Supervised Learning
- Works with **labeled data**
- Learns mapping from input → output  
- Examples:
  - Linear Regression
  - Logistic Regression

---

### 2️ Unsupervised Learning
- Works with **unlabeled data**
- Finds hidden patterns or structures  
- Examples:
  - K-Means Clustering
  - Hierarchical Clustering

---

### 3️ Reinforcement Learning
- Learns through **rewards and penalties**
- Used in dynamic environments  
- Examples:
  - Game AI
  - Robotics

---

##  Machine Learning Workflow

1.  Data Collection  
2.  Data Cleaning  
3.  Feature Engineering  
4.  Model Training  
5.  Model Evaluation  
6.  Deployment  

---

##  Real-World Applications

-  Recommendation Systems (Netflix, Amazon)  
-  Fraud Detection  
-  Self-Driving Cars  
-  Chatbots & Virtual Assistants  

---

##  Tools & Technologies

- Python 
- NumPy  
- Pandas  
- Scikit-learn  

---

##  Simple Example (Linear Regression)

```python
from sklearn.linear_model import LinearRegression
import numpy as np

# Sample data
X = np.array([[1], [2], [3], [4], [5]])
y = np.array([2, 4, 6, 8, 10])

# Model
model = LinearRegression()
model.fit(X, y)

# Prediction
prediction = model.predict([[6]])

print("Prediction for input 6:", prediction[0])
