# 💳 MLPC_fraud_detection: Credit Card Fraud Detection with SMOTE + MLP

This repository delivers a full, modular pipeline for detecting credit card fraud using real-world transaction data and modern automation standards. Built with industry-grade Python libraries and best practices, it demonstrates readiness for production use and business automation roles—like those at ElevenLabs.

## 🔥 Key Features

- **End-to-End Fraud Detection Workflow**
  - Data ingestion and cleaning
  - Exploratory analysis (visualization with seaborn, matplotlib)
  - Feature engineering and selection
  - Imbalanced class handling with SMOTE (Synthetic Minority Over-sampling Technique)
  - Model training with Multi-layer Perceptron Classifier (MLPC - neural network)
  - Evaluation and explainability

- **Tech Stack**
  - Python, Pandas, Numpy, Scikit-learn, Joblib, Seaborn, Imbalanced-learn

- **Scalable and Reproducible**
  - Modular code structure and repeatable experiment setup
  - Model serialization with Joblib for automated deployment
  - Clear, commented notebook for fast prototyping and business-ready insights

- **Business Value**
  - Rapidly flag fraudulent activity in financial data streams
  - Ready for integration into enterprise anti-fraud or ops automation stacks
  - Strong handling and reporting for real-world imbalanced data

## 🚀 How to Run

1. Install dependencies:  
```

pip install -r requirements.txt

```

2. Execute the main pipeline:  
- Prepare and balance dataset  
- Train and evaluate the model  
- Save and reuse the trained model

3. (Optional) Review the included notebook for interactive analysis or rapid prototyping.

## 🛠️ Production & Automation Attributes

- **Automatable pipeline:** Plug-and-play model serialization for integration with internal ops tools or workflow agents.
- **Metrics-driven:** Includes confusion matrix and ROC analysis for direct business KPIs.
- **Extensible:** Swap classifier or oversampling methods for custom team requirements.

## 🏢 Role Relevance for Automation Engineering

This project directly aligns with engineering roles focused on:
- Building AI-driven automated solutions for real business problems
- Designing, deploying, and optimizing workflows (Python-first, automation-ready)
- Using ML/AI to add measurable business value in B2B finance or operations

## 📄 License

MIT License

---

*Inspired by a popular Kaggle dataset: https://www.kaggle.com/mlg-ulb/creditcardfraud*
