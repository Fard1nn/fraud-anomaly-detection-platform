# fraud-anomaly-detection-platform
Real-time ML platform for detecting fraud in financial transactions

## 🚀 Project Overview

This project aims to build a modular fraud detection system using unsupervised and supervised machine learning techniques. The system is designed to operate on both historical (batch) and real-time (streaming) transaction data. The focus is on transparency, scalability, and reliability.

## ✅ Core Features

- Batch anomaly detection using [PyOD](https://github.com/yzhao062/pyod)
- Real-time stream detection using [River](https://riverml.xyz)
- Model explainability with SHAP
- Integration-ready API design (to be implemented)
- Monitoring capabilities (to be implemented)
- Dataset: Kaggle Credit Card Fraud Detection

## 📁 Project Structure

```bash
fraud-anomaly-detection-platform/
├── data/             # Sample/processed data (do not commit sensitive data)
├── models/           # Trained models (optional, .gitignored)
├── notebooks/        # Jupyter notebooks for experiments
├── reports/          # Technical documentation, research summaries
├── src/              # (To be added) Source code for pipelines and APIs
├── requirements.txt  # Python dependencies
├── README.md         # This file 