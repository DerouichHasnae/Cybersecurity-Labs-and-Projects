Lab 2 – Malware Detection using Machine Learning

Objective: Build and evaluate machine learning models to detect malicious Windows executable (PE) files.

Main tasks:

Dataset exploration and data cleaning.

Feature engineering and preprocessing.

Training and comparing machine learning models.

Model evaluation using PR-AUC, precision, recall and F1-score.

Threshold optimization based on classification costs.

Prediction latency measurement.

Model explainability using SHAP.

Final architecture recommendation for AtlasPay.

Models evaluated:

Logistic Regression

Deep Decision Tree

Random Forest

Best validation PR-AUC: Logistic Regression – 0.9080.

Final test results:

Precision: 96.64%

Recall: 89.44%

F1-score: 0.929

False Positives: 10

False Negatives: 34

Prediction latency: 1.953 ms per 1,000 files.

Tools and Technologies:

Python

Jupyter Notebook

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

SHAP
