# Password Strength Prediction using Deep Learning

This repository contains research work on password strength prediction and classification using machine learning and deep learning techniques. The project investigates the effectiveness of neural architectures for estimating password strength and comparing performance across multiple models using standard evaluation metrics.

## Overview

Weak passwords remain one of the most common cybersecurity vulnerabilities. Traditional rule-based password evaluation systems often fail to capture semantic and structural patterns present in real-world passwords.

This project explores data-driven approaches for password strength classification using machine learning and deep learning models trained on large-scale password datasets.

## Objectives

- Develop models for password strength prediction
- Compare traditional ML and deep learning approaches
- Evaluate robustness using multiple classification metrics
- Analyze ROC performance and confusion matrices
- Investigate practical applications in cybersecurity systems

## Models Used

- Random Forest
- LSTM Neural Network
- Transformer-based Model

## Technologies

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

This project utilizes large-scale password datasets for training and evaluation.

Due to size and licensing considerations, the full dataset is not included in this repository.

## Results

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix Analysis

The repository includes:
- ROC curves
- Confusion matrices
- Comparative model performance visualizations

## Research Paper

The accompanying manuscript is currently under review at SN Computer Science (Springer).

The paper is included in the `paper/` directory for academic and reproducibility purposes.

## Reproducibility

### Installation

```bash
pip install -r requirements.txt
```

### Run Notebook

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
- Explainable AI for password strength interpretation

## License

This project is licensed under the MIT License.

## Author

Shivaansh Sharma
