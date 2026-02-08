🧠 Breast Cancer Prediction Using Neural Networks (PyTorch)
📌 Overview

This project is the Day 30 submission of my 30 Days / 30 Machine Learning Projects Challenge.
It focuses on predicting whether a breast tumor is benign or malignant using a Neural Network built with PyTorch.

Beyond accuracy, this project highlights how deep learning can be applied to real-world healthcare problems, where predictions can support early diagnosis and decision-making.

🎯 Problem Statement

Breast cancer is one of the most common cancers worldwide.
Early and accurate detection significantly improves survival rates.

The goal of this project is to:

Analyze diagnostic features of breast tumors

Train a neural network to classify tumors as Benign (0) or Malignant (1)

📊 Dataset

Source: Breast Cancer Wisconsin (Diagnostic) Dataset

Features: 30 numerical features computed from digitized images of breast mass

Target:

0 → Benign

1 → Malignant

🛠️ Tech Stack

Python

PyTorch

NumPy

Pandas

Scikit-learn

Matplotlib

🧠 Model Architecture

Input Layer → 30 features

Hidden Layers → Fully Connected (ReLU activation)

Output Layer → Sigmoid activation

Loss Function → Binary Cross Entropy

Optimizer → Adam

⚙️ Workflow

Load and explore the dataset

Data preprocessing and normalization

Train-test split

Build neural network using PyTorch

Train the model

Evaluate performance on test data

Generate predictions

📈 Results

Achieved high classification accuracy on test data

Model effectively distinguishes between benign and malignant tumors

Demonstrates the practical usability of neural networks in medical prediction tasks

🚀 How to Run
pip install torch numpy pandas scikit-learn matplotlib
python train.py

📌 Key Learnings

Building neural networks from scratch using PyTorch

Handling medical datasets responsibly

Applying deep learning to real-world classification problems

Importance of consistency over perfection (30 days proved that)

🏁 Final Note

This project marks the completion of my 30 Days / 30 ML Projects Challenge — a journey filled with learning, discipline, and persistence.

This is not the end.
This is the foundation.
