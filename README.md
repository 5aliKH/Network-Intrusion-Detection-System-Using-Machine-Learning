# Network Intrusion Detection System Using Machine Learning

## Overview

This project presents a Machine Learning-based Intrusion Detection System (IDS) developed using the CICIDS2017 cybersecurity dataset. The system is designed to detect and classify malicious network activities by analyzing network traffic features and identifying various attack categories.

The project applies Decision Tree Classification combined with Feature Selection techniques to improve detection performance while reducing computational complexity.

It demonstrates how Artificial Intelligence can be used to strengthen network security and detect cyber threats in real-world environments.

---

## Objectives

* Detect malicious network traffic.
* Classify different cyberattack categories.
* Improve detection accuracy using feature selection.
* Evaluate model performance using multiple machine learning metrics.
* Demonstrate practical applications of AI in cybersecurity.

---

## Dataset

### CICIDS2017 Dataset

The project utilizes the CICIDS2017 dataset, one of the most widely used datasets for intrusion detection research.

The dataset contains realistic network traffic and multiple attack scenarios including:

* Botnet Attacks
* Denial of Service (DoS)
* Distributed Denial of Service (DDoS)
* Port Scanning
* Infiltration Attacks
* Heartbleed Attacks
* Benign Traffic

---

## Machine Learning Pipeline

### Data Preprocessing

* Data cleaning
* Missing value handling
* Feature normalization
* Dataset balancing
* Train/Test splitting

### Feature Engineering

Recursive Feature Elimination (RFE) was used to identify the most significant network traffic features contributing to attack detection.

### Classification Model

* Decision Tree Classifier
* Feature Selection Optimization
* Cross Validation Evaluation

---

## Attack Categories Detected

### Botnet Detection

Detects malicious automated network activities.

### DoS & DDoS Detection

Identifies traffic flooding attacks targeting service availability.

### Port Scan Detection

Recognizes reconnaissance activities performed by attackers.

### Infiltration Detection

Detects unauthorized access attempts and suspicious internal activities.

---

## Technologies Used

### Programming Language

* Python

### Machine Learning

* Scikit-Learn
* Decision Tree Classifier
* Recursive Feature Elimination (RFE)

### Data Analysis

* Pandas
* NumPy

### Visualization

* Matplotlib

### Notebook Environment

* Jupyter Notebook

---

## Project Workflow

```text
Raw Network Traffic
        │
        ▼
Data Cleaning
        │
        ▼
Feature Selection (RFE)
        │
        ▼
Decision Tree Training
        │
        ▼
Cross Validation
        │
        ▼
Attack Classification
        │
        ▼
Performance Evaluation
```

---

## Model Evaluation Metrics

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Cross Validation
* Feature Ranking

These metrics provide a comprehensive assessment of intrusion detection performance.

---

## Key Features

* Multi-class attack detection.
* Feature importance analysis.
* Automated data preprocessing.
* Cross-validation testing.
* Optimized feature selection.
* Large-scale cybersecurity dataset support.

---

## Educational Value

This project demonstrates:

* Cybersecurity analytics.
* Machine Learning for network security.
* Intrusion Detection Systems (IDS).
* Feature selection techniques.
* Decision Tree classification.
* Security data science workflows.

---

## Future Improvements

* Random Forest implementation.
* XGBoost integration.
* Deep Learning IDS models.
* Real-time packet analysis.
* SIEM integration.
* Live network monitoring dashboard.
* Explainable AI (XAI) for attack interpretation.

---

## Author

Developed as a Cybersecurity and Machine Learning project for network intrusion detection using the CICIDS2017 dataset and Decision Tree Classification techniques.
