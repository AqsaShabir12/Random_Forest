# Random Forest Classifier from Scratch 

This repository provides a clean and concise implementation of a **Random Forest Classifier** from scratch using **Python** and **NumPy**, without relying on high-level machine learning libraries like `scikit-learn`. The model is tested on the **Breast Cancer Wisconsin Dataset** and demonstrates the power of ensemble methods in classification tasks.

---

## Project Structure

- **DecisionTree.py**  
  Implements a custom decision tree with information gain, entropy, and recursive splitting.

- **RandomForest.py**  
  Implements the `RandomForest` class by creating an ensemble of decision trees trained on bootstrapped samples.

- **main.py** 
  Loads dataset, trains the model, predicts, and computes accuracy.

---

## Requirements

Install the necessary packages with:

```bash
pip install numpy scikit-learn

```

## How to Run
Simply execute the script in your terminal:
```bash
python train.py
```
This will:

- Load the Breast Cancer dataset from scikit-learn
- Split it into training and testing sets
- Train a random forest consisting of multiple decision trees
- Predict the labels of the test set
- Output the classification accuracy

## Dataset

The dataset used is the [Breast Cancer Wisconsin Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html) provided by scikit-learn. It consists of 30 numerical features computed from digitized images of fine needle aspirates (FNA) of breast masses.

