# Credit-Card-Fraud-Detection
Objective:
To build a classification model that detects fraudulent transactions (or anomalies) from a dataset. The dataset is highly imbalanced, meaning fraud cases are rare, so resampling techniques like ADASYN were used to balance the data.

Steps Taken:

Data Preprocessing: Cleaned and prepared data for model training.
Resampling Techniques: Used ADASYN to handle class imbalance and improve fraud detection.
Model Training: Trained a classification model (Logistic Regression, Random Forest, etc.).
Hyperparameter Tuning: Optimized model parameters to improve accuracy.
Evaluation: Measured model performance using Confusion Matrix, Precision-Recall, and ROC-AUC Curve.

ey Points:

Challenge: Detecting rare fraudulent transactions among many normal ones (class imbalance)
Impact:

Protects customers from financial loss
Helps banks prevent fraud in real-time
Reduces financial crime



Results Show:

XGBoost performed best (94% precision in fraud detection)
Neural Network was second-best (76% precision)
Both models are practically useful for fraud detection

Project Strengths:

Used multiple models for comparison
Handled class imbalance
Comprehensive evaluation metrics
Good fraud detection rates
