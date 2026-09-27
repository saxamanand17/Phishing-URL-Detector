# Phishing URL Detector

A machine learning-powered web application that detects potentially phishing URLs by analyzing their structural and linguistic characteristics.

The application provides URL feature extraction, machine learning model training, model evaluation, feature analysis, and real-time URL testing through a Streamlit interface.

## Features

- Comprehensive URL feature extraction
- Analysis of 25+ URL characteristics
- Multiple machine learning algorithms:
  - Random Forest
  - Support Vector Machine (SVM)
  - Logistic Regression
- Interactive Streamlit web interface
- Model performance evaluation
- Confusion matrix and classification reports
- Feature importance analysis
- Real-time URL classification
- Individual URL feature analysis
- Support for custom training datasets

## Technology Stack

- **Python**
- **Streamlit** — Web interface
- **scikit-learn** — Machine learning
- **Pandas** — Data processing
- **NumPy** — Numerical operations
- **Matplotlib** — Visualization
- **Seaborn** — Visualization
- **urllib** — URL processing
- **tld** — Domain/TLD processing
- **Regular Expressions** — Pattern analysis

## How It Works

The system follows a machine-learning-based URL analysis workflow:

```text
URL
 │
 ▼
Feature Extraction
 │
 ├── URL structure
 ├── Domain properties
 ├── Path and query characteristics
 ├── Special characters
 └── Suspicious patterns
 │
 ▼
Machine Learning Models
 │
 ├── Random Forest
 ├── SVM
 └── Logistic Regression
 │
 ▼
Prediction
 │
 ├── Phishing
 └── Legitimate