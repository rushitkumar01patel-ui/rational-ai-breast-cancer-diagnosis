# rational-ai-breast-cancer-diagnosis
A case study exploring rationality constraints in machine intelligence for breast cancer diagnosis using Logistic Regression and Naïve Bayes on the Wisconsin Diagnostic Breast Cancer dataset, developed as part of the Foundations of Artificial Intelligence coursework.

## Understanding Rationality Constraints in Machine Intelligence for Breast Cancer Diagnosis

This repository presents an academic case study examining how machine intelligence systems make rational decisions under uncertainty in the context of breast cancer diagnosis.

The project applies classical machine learning models to the Breast Cancer Wisconsin (Diagnostic) Dataset (WDBC) and evaluates their behaviour using utility-driven metrics that reflect real-world clinical priorities.

Project Aim

📌 Project Overview

Breast cancer diagnosis is a high-stakes medical decision problem where incorrect predictions can have serious consequences. This project applies the concept of rational agents from Artificial Intelligence to evaluate how machine learning models behave when faced with uncertainty, limited information, and uneven error costs.

Using the Breast Cancer Wisconsin (Diagnostic) Dataset (WDBC), the study compares two classical machine learning approaches:

Logistic Regression

Naïve Bayes Classifier

The focus is not only on predictive performance, but also on computational rationality, utility-based evaluation, and bounded rationality in medical AI systems.

🎯 Objectives

Model breast cancer diagnosis as a rational agent problem

Compare decision-making behaviour of Logistic Regression and Naïve Bayes

Evaluate models using clinically meaningful metrics

Analyse trade-offs between accuracy, recall, precision, and robustness

Critically reflect on limitations related to data, fairness, and sustainability

🧠 AI Concepts Applied

Rational agents and utility maximisation

Computational rationality

Bounded rationality (Simon)

Metric-based decision trade-offs

Ethical and sustainability considerations in medical AI

📂 Dataset

Source: UCI Machine Learning Repository

Dataset: Breast Cancer Wisconsin (Diagnostic)

Samples: 569

Features: 30 numeric attributes derived from FNA images

Classes:

Malignant (1)

Benign (0)

Missing Values: None

🛠️ Models Implemented
Logistic Regression

Probabilistic linear classifier

High interpretability

Suitable for transparent clinical decision support

Naïve Bayes Classifier

Probabilistic model based on Bayes’ theorem

Assumes conditional independence between features

Computationally efficient under uncertainty

📊 Evaluation Strategy

The models are evaluated using a utility-aware framework, recognising that false negatives are clinically more dangerous than false positives.

Metrics Used:

Recall – prioritises detection of malignant cases

Precision – limits unnecessary clinical interventions

F1-Score – balances recall and precision

ROC-AUC – evaluates robustness across decision thresholds

Validation Methods:

Train/Test Split

k-Fold Cross-Validation

⚖️ Key Findings

High recall is critical for rational medical decision-making

Metric trade-offs reflect real-world clinical priorities

Simpler models can still perform rationally under uncertainty

No model achieves perfect rationality due to data and resource constraints

🧩 Bounded Rationality & Ethics

This project acknowledges several limitations:

Dataset does not represent all patient populations

Potential fairness issues due to under-representation

Computational sustainability concerns with complex models

Risk of misclassification for non-average cases

Recognising these constraints is essential for responsible deployment of AI in healthcare.

🧪 Technologies Used

Python

NumPy

Pandas

Scikit-learn

Matplotlib / Seaborn
