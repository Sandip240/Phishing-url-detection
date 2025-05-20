# Phishing URL Detection using Machine Learning

## Project Overview
This project uses a machine learning approach to classify URLs as legitimate or phishing. It helps organizations, especially in the banking sector, to identify and block malicious phishing links.

## Tech Stack
- Python
- Pandas, Scikit-learn
- Random Forest Classifier
- Joblib

## Dataset
- 10,000+ URLs labeled as `0` (Legitimate) or `1` (Phishing)
- Features include structural and domain-based URL characteristics

## Results
- Accuracy: **98%**
- Model: `RandomForestClassifier`
- Exported model: `phishing_url_model.pkl`
