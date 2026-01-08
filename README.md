# CreditCardFraudDetection
Unsupervised Credit Card Fraud Detection using PyOD (KNN, LODA, OCSVM) on a highly imbalanced dataset.
## Project Overview
This project focuses on identifying fraudulent credit card transactions using unsupervised machine learning techniques. Given the extreme class imbalance (0.17% fraud rate), I implemented and compared three different anomaly detection algorithms from the PyOD library.

## Key Features
* Data Preprocessing: Robust cleaning (handling missing/infinite values) and feature scaling using StandardScaler.

* Dynamic Contamination: Automatically calculates the outlier threshold based on the actual class distribution.

## Algorithms Implemented:

* KNN (K-Nearest Neighbors): For distance-based density detection.

* LODA (Lightweight Online Detector): Fast, histogram-based ensemble method for high-dimensional data.

* One-Class SVM: Boundary-based detection using RBF kernel.

## Evaluation Metrics: 
* Evaluated model performance using clustering-specific metrics: Silhouette Score, Dunn Index, Calinski-Harabasz, and Davies-Bouldin.

## Results
* KNN and LODA achieved high Silhouette scores (~0.85), proving efficient at identifying clustered anomalies.

* One-Class SVM showed higher sensitivity, flagging a broader range of suspicious transactions.

## Technologies Used
* Python

* PyOD (Python Outlier Detection)

* Scikit-Learn

* Pandas & NumPy

* Matplotlib & Seaborn (Data Visualization)
