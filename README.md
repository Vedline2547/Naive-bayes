# 🧠 Gaussian Naive Bayes Classifier

A simple **Machine Learning classification project** using Scikit-learn's `GaussianNB` algorithm.

The model is trained on a small sample dataset to predict whether a student will **Pass (1)** or **Fail (0)** based on two numerical features.

## 📌 Project Overview

This project demonstrates how to:

* Create a dataset using NumPy
* Split data into training and testing sets
* Implement a Gaussian Naive Bayes classifier
* Train the model
* Make predictions on unseen data
* Evaluate the model using:

  * Accuracy
  * Confusion Matrix

## 🧠 Machine Learning Algorithm

### Gaussian Naive Bayes

**Naive Bayes** is a supervised machine learning algorithm based on **Bayes' theorem**.

Gaussian Naive Bayes is a variant of Naive Bayes designed for classification problems where the features are continuous numerical values.

The algorithm assumes that the features follow a **Gaussian (normal) distribution** within each class.

In this project:

* `0` → Fail
* `1` → Pass

## 📊 Dataset

The project uses a small manually created dataset.

### Features

The input dataset contains two numerical features:

```text
[1, 50]
[3, 60]
[3, 55]
[4, 65]
[5, 70]
[6, 75]
[7, 80]
[8, 85]
[9, 90]
[10, 95]
```

### Target Variable

| Value | Meaning |
| ----- | ------- |
| `0`   | Fail    |
| `1`   | Pass    |

For example:

```text
[4, 65] → Fail
[7, 80] → Pass
```

## 🛠️ Technologies Used

* **Python**
* **NumPy**
* **Scikit-learn**

### Libraries

```python
import numpy as np

from sklearn.naive_bayes import GaussianNB
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score, confusion_matrix
```

## ⚙️ Project Workflow

```text
Create Dataset
      ↓
Split Dataset
      ↓
Initialize GaussianNB
      ↓
Train Model
      ↓
Make Predictions
      ↓
Evaluate Model
      ↓
Accuracy + Confusion Matrix
```

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/Vedline2547/Naive-bayes.git
```

Navigate to the project directory:

```bash
cd Naive Bayes
```

Install the required libraries:

```bash
pip install numpy scikit-learn
```

## ▶️ Running the Project

Run the Python script:

```bash
main.py
```

The program will display the model's accuracy and confusion matrix.

Example:

```text
Accuracy: 1.0
Confusion Matrix:
[[1 0]
 [0 1]]
```

> **Note:** The exact output can vary depending on the train/test split and model configuration.

## 📈 Model Evaluation

### Accuracy

Accuracy measures the proportion of predictions that the model classified correctly.

```text
Accuracy = Correct Predictions / Total Predictions
```

### Confusion Matrix

The confusion matrix provides more detail about the model's classification performance.

```text
[[TN  FP]
 [FN  TP]]
```

Where:

* **TN** → True Negative
* **FP** → False Positive
* **FN** → False Negative
* **TP** → True Positive

## 📁 Project Structure

```text
gaussian-naive-bayes/
│
├── gaussian_naive_bayes.py
└── README.md
```

## ⚠️ Important Note

This project uses only **10 observations**, so it is intended for educational purposes and demonstration of the Gaussian Naive Bayes workflow.

The dataset is too small to provide a reliable estimate of real-world model performance.

For a real-world application, a larger dataset, appropriate preprocessing, and techniques such as **cross-validation** should be used.

## 🎯 Learning Objectives

This project helps demonstrate:

* Supervised learning
* Classification
* Bayes' theorem
* Naive Bayes classification
* Gaussian Naive Bayes
* Training and testing datasets
* Model prediction
* Accuracy evaluation
* Confusion matrices

## 🔮 Future Improvements

Possible improvements include:

* Use a larger real-world dataset
* Visualize the classification results
* Plot the confusion matrix
* Perform cross-validation
* Tune model parameters
* Compare Gaussian Naive Bayes with other classification algorithms
* Add feature names and meaningful real-world data

## 👨‍💻 Author

**Vedline Ochieng**

Civil Engineering Student • Machine Learning Enthusiast • Python Developer • Future AI Engineer

---

⭐ If you found this project useful, consider giving the repository a star!
