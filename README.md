## Fraud Detection Using Machine Learning
# Project Overview
This project applies machine learning techniques to detect fraudulent transactions in an imbalanced dataset. The goal is to build accurate models to identify fraudulent activities while minimizing false positives.

# Features
Imbalanced dataset handling using SMOTE and SMOTEENN.
Autoencoder-based anomaly detection.
Fraud classification using deep learning.
Comprehensive evaluation metrics (ROC-AUC, recall).
# Requirements
Python 3.8+
Libraries:
pandas
numpy
sklearn
imbalanced-learn
keras
# Setup Instructions
Clone the repository:
bash
git clone https://github.com/Priyank-0704/MLP_final_project.git
Navigate to the project directory:
bash
cd project-name
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook:
bash
jupyter notebook fraud_detection.ipynb
Results
The implemented deep learning model achieved:

ROC-AUC score: 0.96
Recall: 92%
Directory Structure
bash

project-name/
│
├── data/                     # Dataset folder (not included in repo for privacy)
├── fraud_detection.ipynb     # Jupyter notebook
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
# Future Scope
Improve generalization by testing on other datasets.
Explore feature importance analysis.
Deployment strategies for real-world application.