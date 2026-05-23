# Password Strength Prediction using Machine Learning and Deep Learning

This repository contains research work focused on password strength prediction and classification using machine learning and deep learning techniques. The project investigates the effectiveness of neural architectures for modeling password complexity patterns and compares their performance against traditional machine learning approaches using multiple evaluation metrics.

## Overview

Weak and predictable passwords continue to be one of the most significant cybersecurity vulnerabilities. Conventional rule-based password evaluators often fail to capture semantic, structural, and sequential patterns present in real-world passwords.

This project explores data-driven approaches for password strength assessment using machine learning and deep learning models trained on large-scale password datasets. The study evaluates the capability of neural architectures to improve password classification performance and better identify complex password characteristics.

## Objectives

- Develop machine learning and deep learning models for password strength prediction
- Compare the effectiveness of traditional ML and neural architectures
- Evaluate model performance using multiple classification metrics
- Analyze ROC performance and confusion matrices
- Investigate practical cybersecurity applications of password strength estimation systems

## Models Implemented

- Random Forest Classifier
- LSTM Neural Network
- Transformer-based Neural Network

## Technologies Used

- Python
- PyTorch
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Repository Structure

```text
password-strength-prediction/
│
├── notebooks/
│   └── password_strength_prediction.ipynb
│
├── figures/
│   ├── lstm_confusion_matrix.png
│   ├── rf_confusion_matrix.png
│   ├── transformer_confusion_matrix.png
│   ├── lstm_roc_curve.png
│   ├── rf_roc_curve.png
│   └── transformer_roc_curve.png
│
├── paper/
│   └── manuscript_under_review_sncs.pdf
│
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

## Dataset

The models were trained and evaluated using large-scale password datasets containing passwords with varying complexity levels and structural characteristics.

Due to dataset size and licensing considerations, the complete dataset is not included in this repository.

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix Analysis

## Key Results

- Deep learning models demonstrated improved classification capability compared to traditional machine learning approaches.
- The Transformer-based architecture achieved the strongest overall predictive performance across evaluation metrics.
- ROC curve analysis showed superior discriminative performance for neural architectures.
- Confusion matrix analysis indicated improved handling of complex password structures by deep learning models.

The repository includes:
- ROC curve visualizations
- Confusion matrices
- Comparative performance figures

## Research Paper

Research project focused on password strength classification using machine learning and neural architectures.

The accompanying manuscript is currently under review at SN Computer Science (Springer).

The paper is included in the `paper/` directory for academic reference and reproducibility purposes.

## Reproducibility

### Installation

```bash
pip install -r requirements.txt
```

### Run the Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/password_strength_prediction.ipynb
```

## Future Work

- Integration of advanced transformer architectures
- Adversarial robustness evaluation
- Real-time password assessment systems
- Explainable AI techniques for password strength interpretation
- Hybrid neural architectures for improved classification performance

## License

This project is licensed under the MIT License.

## Author

Shivaansh Sharma
