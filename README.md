# Face-Recognition


## Overview
An advanced face recognition system designed to accurately identify individuals using a robust image processing pipeline. The system converts images to grayscale and extracts key facial features using Haar Cascade. These features are then serialized using pickle for efficient storage. To optimize the data, Principal Discriminant Analysis (PDA) is employed for dimensionality reduction. Multiple classifiers including Support Vector Machine (SVM), Random Forest, and Logistic Regression—are trained on the processed data, with the SVM classifier achieving the highest accuracy.

## Features
- **Grayscale Conversion:** Simplifies images by converting them to grayscale for efficient processing.
- **Feature Extraction:** Uses Haar Cascade to detect and extract important facial features.
- **Data Serialization:** Saves extracted features in pickle format for quick retrieval and reusability.
- **Dimensionality Reduction:** Employs Principal Discriminant Analysis (PDA) to reduce data complexity while retaining discriminative features.
- **Classifier Training:** Trains various classifiers (SVM, Random Forest, Logistic Regression) to evaluate and compare recognition performance.
- **High Accuracy:** The SVM classifier demonstrates superior accuracy, validating the system's effectiveness.

## Technologies Used
- **Python:** Core programming language used for development.
- **OpenCV:** Utilized for image processing tasks like grayscale conversion and Haar Cascade-based feature extraction.
- **Scikit-learn:** Provides tools for PDA, classifier training, and performance evaluation.
- **Pickle:** Used for serializing and storing extracted feature data.
- **NumPy & Pandas:** For data manipulation and analysis.

## Getting Started

### Prerequisites
- **Python 3.6+**
- **OpenCV**
- **Scikit-learn**
- **NumPy**
- **Pandas**


