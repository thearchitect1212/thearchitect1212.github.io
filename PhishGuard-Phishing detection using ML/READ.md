# PhishGuard: Advanced Machine Learning-Based Phishing Website Detection

## Overview
PhishGuard is a machine learning-based solution designed to detect phishing websites in real-time. By analyzing features inherent to URLs and websites, it provides robust protection against phishing attacks, addressing limitations of traditional detection methods such as blacklists and signature-based systems. PhishGuard employs Random Forest, XGBoost, and deep learning models to achieve high accuracy, adaptability, and scalability.

---

## Key Features
- **Real-Time Detection**: Analyzes URL structures, domain information, and website behaviors to detect phishing sites instantly.
- **Advanced Models**: Utilizes Random Forest, XGBoost, and 1D Convolutional Neural Networks (CNNs).
- **Dynamic Adaptability**: Adapts to evolving phishing tactics such as HTTPS spoofing and homograph attacks.
- **Scalability**: Suitable for integration with browsers, email platforms, and corporate security infrastructures.
- **Ethical AI**: Ensures user privacy, mitigates biases, and provides explainable results.

---

## Dataset
- **Sources**: UCI Machine Learning Repository, PhishTank, and Tranco List.
- **Size**: 11,055 websites (53% phishing, 47% legitimate).
- **Features**:
  - **Address-based**: URL length, IP usage, "@ symbol" presence.
  - **Domain-based**: Domain age, SSL certificate status.
  - **Content-based**: HTML elements, keyword analysis.
- **Preprocessing**:
  - Removed duplicates and handled missing values using imputation.
  - Scaled features using Min-Max scaling.
  - Balanced the dataset with SMOTE (Synthetic Minority Over-sampling Technique).

---

## Machine Learning Models
### 1. Random Forest
- **Accuracy**: 98%
- **Top Features**: SSL validity, URL length, web traffic, domain age.
- **Hyperparameters**: 
  - Trees: 200
  - Max Depth: 15
  - Minimum Samples Split: 2
- **Tuning**: Grid Search with 5-fold cross-validation.

### 2. XGBoost
- **Accuracy**: 98.5%
- **Strengths**: Excellent handling of imbalanced datasets.
- **Hyperparameters**:
  - Learning Rate: 0.1
  - Max Depth: 10
  - Estimators: 150
- **Tuning**: Bayesian optimization.

### 3. Convolutional Neural Networks (CNNs)
- **Accuracy**: 95%
- **Focus**: Sequence patterns in URLs.

---

## Evaluation Metrics
- **Accuracy**: Measures overall correctness.
- **Precision**: Minimizes false positives.
- **Recall**: Effectively captures phishing sites.
- **F1 Score**: Balances precision and recall.
- **AUC-ROC**: Evaluates model distinction between phishing and legitimate websites (AUC = 0.985).

---

## Applications
- **Browser Extensions**: Real-time detection for Chrome, Firefox, and Edge.
- **Email Platforms**: Integration with Outlook and Gmail to analyze phishing links.
- **Mobile Platforms**: SDKs for iOS and Android to detect malicious links in SMS and apps.
- **Enterprise Security**: Integration with corporate systems using APIs and microservices.

---

## Ethical Considerations
- **Privacy**: Compliance with GDPR and CCPA through anonymization techniques.
- **Bias Mitigation**: Trained on diverse datasets to avoid regional or linguistic biases.
- **Explainable AI**: Provides transparent detection decisions to build trust.

---

## Future Directions
1. Expand threat intelligence capabilities, such as dark web monitoring.
2. Incorporate adaptive learning to continuously enhance detection models.
3. Enhance user reporting mechanisms to reduce false positives and improve accuracy.

---

## References
1. Verizon. (2023). 2023 Data Breach Investigations Report.
2. FBI Internet Crime Complaint Center. (2022). Internet Crime Report.
3. PhishTank. Verified phishing URLs database.
4. UCI Machine Learning Repository. Phishing Websites Dataset.

---
