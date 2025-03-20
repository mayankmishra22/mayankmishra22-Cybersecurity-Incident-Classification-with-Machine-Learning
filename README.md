## **Project Overview**
The **Classifying Cybersecurity Incidents** project is designed to enhance the efficiency of **Security Operation Centers (SOCs)** at Microsoft. The project focuses on building a classification model that accurately predicts the triage grade of cybersecurity incidents, assisting SOC analysts in prioritizing their efforts and responding to threats efficiently.

The goal is to classify incidents as:
- **True Positive (TP)**: A confirmed threat.
- **Benign Positive (BP)**: A false alarm.
- **False Positive (FP)**: A misidentified threat.

## **Phases**
This project allows you to dive deep into several crucial aspects of data science and machine learning:
- **Data Preprocessing & Feature Engineering**: Cleaning and transforming raw data into useful features for model training.
- **Machine Learning Classification Techniques**: Employing algorithms like Random Forest, XGBoost, and others for incident classification.
- **Evaluation Metrics**: Using **Macro-F1 Score**, **Precision**, and **Recall** to assess model performance.
- **Cybersecurity Frameworks**: Leveraging the **MITRE ATT&CK** framework for better understanding of cybersecurity data.
- **Handling Imbalanced Datasets**: Implementing strategies like SMOTE, class weights, and ensemble methods to deal with imbalanced data.
- **Model Optimization**: Fine-tuning model parameters for optimal performance.

## **Results**
- **Model Performance**: A highly accurate classification model that predicts cybersecurity incident triage grades (TP, BP, FP).
- **Feature Analysis**: Insights into which features influence model predictions the most.
- **Model Documentation**: Comprehensive process documentation, highlighting each phase from data collection to model evaluation.

## **Evaluation Metrics**
- **Macro-F1 Score**: Balances precision and recall, providing a holistic view of performance across all classes.
- **Precision**: Measures the proportion of true positive predictions out of all positive predictions.
- **Recall**: Measures the model’s ability to identify all true positives, ensuring critical incidents are not missed.

### **Features**:
- **Evidence**: Individual pieces of evidence like IP addresses, emails, and user details.
- **Alerts**: Aggregated evidence signaling a potential security incident.
- **Incidents**: A collection of alerts representing a complete security threat scenario.
