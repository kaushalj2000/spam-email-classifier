# Email Spam Classifier

A machine learning project that builds an intelligent email spam detection system using natural language processing and classification algorithms.

## 🎯 Project Overview

This project demonstrates building a spam classifier using the Apache SpamAssassin dataset. The classifier achieves excellent performance with 96.88% precision and 97.89% recall.

## 🚀 Results

- **Precision: 96.88%** - When the model predicts spam, it's correct 96.88% of the time
- **Recall: 97.89%** - The model successfully identifies 97.89% of all actual spam emails  
- **Cross-validation Accuracy: 98.5%** - Consistent performance across different data splits

## 🛠️ Technologies Used

- **Python**: Core programming language
- **Scikit-learn**: Machine learning framework
- **NLTK**: Natural language processing
- **Pandas/NumPy**: Data manipulation
- **Jupyter Notebook**: Development environment

## 📊 Dataset

- **Source**: Apache SpamAssassin Public Corpus
- **Size**: ~3,000 emails (2,500 ham + 500 spam)

## 🔧 Key Features

- Custom email preprocessing pipeline
- Text feature extraction with bag-of-words
- Logistic regression classifier
- Comprehensive model evaluation
- Handles HTML emails, URLs, and text cleaning

## 📈 How to Run

1. Open the Jupyter notebook: `Spam_classifier.ipynb`
2. Run all cells sequentially
3. The notebook will automatically download the dataset and train the model

## 🎯 Model Performance

The classifier demonstrates excellent performance suitable for real-world spam detection, achieving high precision (minimal false positives) and high recall (catches most spam).
