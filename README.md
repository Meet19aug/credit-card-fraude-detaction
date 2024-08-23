# Credit Card Fraud Detection

## Project Overview
This project focuses on the detection of credit card fraud using advanced data science techniques. With the increasing incidents of fraud, particularly in the financial sector, it is imperative to develop robust systems that can detect fraudulent activities in real time. This project leverages both traditional rule-based approaches and modern machine learning methods to identify fraudulent transactions.

## Team Members
- **Hemang Parekh** (19CP066)
- **Jainil Patel** (19CP067)
- **Meet Patel** (19CP072)

## Table of Contents
1. [Introduction](#introduction)
2. [Types of Fraud](#types-of-fraud)
3. [Detection Approaches](#detection-approaches)
   - [Rule-Based Approach](#rule-based-approach)
   - [Data Science Approach](#data-science-approach)
4. [Challenges](#challenges)
5. [Data Handling Techniques](#data-handling-techniques)
6. [Demo](#demo)
7. [Conclusion](#conclusion)

## Introduction
Fraud is a deliberate act of deception aimed at securing unfair or unlawful financial gain. The financial sector, especially credit card transactions, is particularly vulnerable to fraud. According to recent reports, a typical organization loses about 5% of its revenue to fraud.

## Types of Fraud
### Online Fraud
Involves deceptive practices conducted over the internet to steal money or sensitive information.

### Credit Card Fraud
A significant threat to financial institutions, involving unauthorized transactions using stolen or counterfeit credit cards.

### Inventory Fraud
Manipulation of inventory data to inflate assets or conceal losses.

## Detection Approaches

### Rule-Based Approach
- **Description**: A traditional method where algorithms are written by fraud analysts based on predefined rules.
- **Challenges**:
  - Time-consuming and costly.
  - Cannot recognize hidden patterns.
  - Ineffective against new, untrained situations.

### Data Science Approach
- **Machine Learning (ML)**: Encompasses a range of algorithms and techniques for classification, regression, clustering, and anomaly detection.
- **Deep Neural Networks (DNNs)**: Advanced models capable of capturing complex patterns in data for fraud detection.
- **Supervised Learning**: Requires labeled data; challenges include dealing with unbalanced datasets.
- **Unsupervised Learning**: Techniques like PCA and K-means clustering are used for pattern recognition without labeled data.

## Challenges
- **Unbalanced Data**: Less than 0.5% of credit card transactions are fraudulent, making it difficult to train models.
- **Operational Efficiency**: Systems need to flag fraudulent transactions in under 8 seconds to avoid delays.
- **Incorrect Flagging**: It is crucial to minimize false positives to avoid harassing legitimate customers.

## Data Handling Techniques

### Sampling Methods
- **Random Over-Sampling**: Increases the number of fraud cases in the dataset by duplicating minority class samples.
- **Random Under-Sampling**: Reduces the number of non-fraud cases to balance the dataset.
- **SMOTE (Synthetic Minority Over-Sampling Technique)**: Generates synthetic samples of the minority class (fraud cases) to balance the dataset.

### Visualization
- **Scatter Plots**: Used to visualize class distribution before and after applying different sampling techniques.

## Demo
The project includes a practical demonstration of the fraud detection process, showcasing the application of machine learning models on real-world data to detect fraudulent credit card transactions.

## Conclusion
This project highlights the importance of using both traditional and modern techniques to combat credit card fraud. By leveraging machine learning, we can build more effective and adaptive systems that respond to evolving fraud patterns.
