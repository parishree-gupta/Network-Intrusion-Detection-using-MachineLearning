# Network Intrusion Detection System Documentation

## Project Overview

This project implements a **Network Intrusion Detection System (NIDS)** using Machine Learning and Deep Learning techniques on the **NSL-KDD** dataset. The repository has been modernized to run on **Google Colab**, supporting **Python 3.12**, **TensorFlow/Keras 3**, **NumPy 2.x**, and **pandas 2.x**.

The objective of the project is to classify network traffic as either **normal** or **malicious**, enabling early detection of cyber attacks through intelligent data analysis.

---

# Objectives

* Detect malicious network traffic using Machine Learning algorithms.
* Build and evaluate an LSTM-based Deep Learning model.
* Compare the performance of different classification techniques.
* Provide a Google Colab compatible implementation using the latest Python ecosystem.

---

# Project Workflow

The overall workflow of the project is shown below.

1. Load the NSL-KDD dataset.
2. Perform data preprocessing.
3. Encode categorical features.
4. Normalize numerical features.
5. Perform feature engineering.
6. Train multiple Machine Learning models.
7. Train the LSTM-based Deep Learning model.
8. Evaluate model performance.
9. Predict network intrusions.

---

# Project Structure

```text
Network-Intrusion-Detection-using-MachineLearning/

│
├── Data_Preprocessing_NSL_KDD.ipynb
├── Classifiers_NSL_KDD.ipynb
├── Intrusion_Detection_NSL_KDD.ipynb
│
├── datasets/
├── images/
├── labels/
├── plots/
│
├── README.md
├── documentation.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# Notebook Description

## 1. Data_Preprocessing_NSL_KDD.ipynb

This notebook is responsible for preparing the dataset for model training.

### Tasks Performed

* Dataset loading
* Data cleaning
* Handling missing values
* Label encoding
* Feature scaling
* Binary and multi-class dataset generation

### Outputs

* Processed datasets
* Encoded labels
* Scaled features

---

## 2. Classifiers_NSL_KDD.ipynb

This notebook trains and evaluates several Machine Learning models.

### Implemented Models

* Decision Tree
* Random Forest
* Logistic Regression
* K-Nearest Neighbors
* Naive Bayes
* Support Vector Machine

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* ROC Curve
* Confusion Matrix

---

## 3. Intrusion_Detection_NSL_KDD.ipynb

This notebook implements the Deep Learning model for intrusion detection.

### Deep Learning Architecture

* LSTM Layer
* Dense Output Layer

### Model Evaluation

* Training Accuracy
* Validation Accuracy
* Training Loss
* Validation Loss
* ROC Curve

---

# Dataset

The project uses the **NSL-KDD** dataset, a widely used benchmark dataset for intrusion detection research.

The dataset contains normal network traffic as well as multiple categories of attacks, making it suitable for evaluating cybersecurity models.

Due to repository size limitations, the dataset is not included. Refer to `datasets/README.md` for download instructions.

---

# Technologies Used

## Programming Language

* Python

## Libraries

* TensorFlow / Keras
* Scikit-learn
* NumPy
* Pandas
* Matplotlib
* Seaborn
* SciPy
* Joblib

## Development Environment

* Google Colab
* Jupyter Notebook

---

# Performance Evaluation

The models are evaluated using standard classification metrics.

* Accuracy
* Precision
* Recall
* F1-Score
* ROC Curve
* Confusion Matrix

Performance graphs such as training accuracy, training loss, and ROC curves are included in the `images/` directory.

---

# Modernization

The original implementation has been updated to support modern software versions.

### Improvements

* Google Colab compatibility
* Python 3.12 compatibility
* TensorFlow/Keras 3 support
* NumPy 2.x compatibility
* pandas 2.x compatibility
* Updated deprecated APIs
* Improved notebook stability

---

# Future Enhancements

Potential improvements include:

* Real-time packet capture
* Live network monitoring dashboard
* Explainable AI (XAI)
* REST API integration
* Docker containerization
* Cloud deployment
* Streaming intrusion detection

---

# How to Run

1. Clone the repository.
2. Install dependencies from `requirements.txt`.
3. Download the NSL-KDD dataset.
4. Place the dataset inside the `datasets/` directory.
5. Open the notebooks in Google Colab.
6. Execute the notebooks in the following order:

   1. Data_Preprocessing_NSL_KDD.ipynb
   2. Classifiers_NSL_KDD.ipynb
   3. Intrusion_Detection_NSL_KDD.ipynb

---

# Author

**Pari Shree Gupta**

B.Tech Computer Science Engineering

Jaypee Institute of Information Technology

GitHub: https://github.com/parishree-gupta

---

# License

This project is distributed under the MIT License.
