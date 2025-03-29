# anomaly-detection

## 🚀 Web Authentication Anomaly Detection

## 🔍 Overview

This project focuses on detecting anomalies in web authentication systems using supervised and unsupervised machine learning techniques. The goal is to enhance security by identifying suspicious login behaviors that could indicate unauthorized access attempts. Currently, the repo includes a supervised learning approach, with plans to add an unsupervised model soon.

# 📁 Repo Structure

- AD_Analysis.ipynb – Jupyter notebook implementing multiple supervised learning models for anomaly detection.
- data/ – Contains synthetic datasets used for training and testing.

# 📊 Dataset

A synthetic dataset simulating real-world login attempts, with features like:

- User ID – Unique identifier per user.
- Timestamp – Login date & time.
- Login Status – Success or failure.
- IP Address – Source of login attempt.
- Device Type – Mobile, tablet, or desktop.
- Location – Geo-location of the login.
- Session Duration – Active session length.
- Failed Attempts – Number of previous failed logins.
- Behavioral Score – User behavior pattern to detect deviations.

# 🎯 Goals
- ✅ Generate realistic synthetic datasets for model training.
- ✅ Implement ML models to classify login activities as normal or suspicious.
- ✅ Evaluate models based on accuracy, precision, recall, and ROC-AUC scores.

# 📌 Insights
Performance Evaluation – Metrics for models like Logistic Regression, Random Forest, SVM, and Neural Networks.
Feature Importance – Identify key factors that indicate anomalies.
Predictive Power – Models effectively differentiate between normal and abnormal behavior.

# 🚧 Future Enhancements
🔹 Unsupervised Learning Approach – Coming soon! Detect anomalies without labeled data.
