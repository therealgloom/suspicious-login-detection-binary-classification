Suspicious Login Detection — Binary Classification

Overview

This project applies supervised machine learning to classify network connections as normal or malicious using the NSL-KDD dataset.

The task is formulated as a binary classification problem:

- "0": Normal connection
- "1": Malicious connection

Objectives

- Explore network traffic features for intrusion detection.
- Build a Logistic Regression classification model.
- Compare model performance against a dummy baseline.
- Evaluate performance using accuracy, precision, recall, F1-score, and ROC-AUC.

Methodology

The project covers data preprocessing, feature engineering, model training, and performance evaluation. Five-fold cross-validation is used to assess model performance across multiple data splits.

Key Result

The Logistic Regression model achieved a mean ROC-AUC of 0.9965 across five-fold cross-validation.

This result indicates strong discrimination between normal and malicious connections within the NSL-KDD dataset. It should not be interpreted as a guarantee of equivalent performance on real-world network traffic.

Limitations

NSL-KDD is a simulated benchmark dataset. Real-world environments may contain different traffic patterns, new attack techniques, and previously unseen threats.

Project File

- "suspicious_login_detection.ipynb" — Notebook containing the analysis, model development, and evaluation.

Tools

Python, pandas, scikit-learn, and Jupyter Notebook.

Disclaimer

This is an educational portfolio project and is not intended to serve as a production-ready intrusion detection system.


