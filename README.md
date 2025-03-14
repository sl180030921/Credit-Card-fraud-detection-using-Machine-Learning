# Credit Card Fraud Detection System Using Machine Learning
## Overview
This project aims to detect fraudulent credit card transactions using machine learning techniques. The dataset consists of 300,000 anonymized transactions, where fraudulent transactions make up less than 0.1% of the total data. Due to this severe imbalance, special techniques like SMOTE (Synthetic Minority Over-sampling Technique) were implemented to improve fraud detection.

### Problem Statement
Traditional fraud detection systems relied on rule-based approaches, which were limited in their adaptability. The objective of this project is to leverage machine learning models to develop an intelligent fraud detection system that can:
✔ Identify fraudulent transactions with high precision and recall.
✔ Handle the class imbalance problem effectively.
✔ Improve scalability and real-time detection capabilities.

### Techniques Used
This project explores various machine learning and deep learning models to compare their effectiveness in detecting fraudulent transactions:

1. Machine Learning Approaches
🔹 Random Forest – Ensemble method that improves generalization by training multiple decision trees.
🔹 Decision Trees – Simple interpretable model that can capture patterns in the data.

2. Deep Learning Approaches
🔹 Neural Networks – Fully connected layers trained to classify transactions as fraudulent or non-fraudulent.

3. Handling Class Imbalance
Since fraud cases are extremely rare, different techniques were implemented to improve the model's ability to detect fraudulent transactions:
✔ SMOTE (Synthetic Minority Over-sampling Technique) – Generates synthetic fraud cases to balance the dataset.
✔ Class Weight Adjustment – Assigning higher weight to fraudulent transactions in the loss function.
✔ Under-sampling the Majority Class – Reducing non-fraudulent transactions to balance the dataset.

### Results & Key Findings
📌 The best performance was achieved using SMOTE + Neural Network, which detected 100% of fraud cases while maintaining a low false positive rate.
📌 Random Forest outperformed Decision Trees, showing higher accuracy and better generalization.
📌 Deep Learning models improved performance significantly, especially when trained with weighted loss functions and oversampled data.

## Acknowledgment
This project was forked from an open-source repository: [[Original Repository Link](https://github.com/LaurentVeyssier/Credit-Card-fraud-detection-using-Machine-Learning)]. I have modified and extended the project by adding (mention any modifications you made, e.g., new models, data preprocessing, visualization, deployment, etc.).

