# Intrusion Detection Model for IoT-Enabled Smart Homes 

## 📌 Overview

This project presents a machine learning-based Intrusion Detection System (IDS) designed for IoT-enabled smart homes. With the rise of IoT devices, ensuring the security of network traffic has become increasingly important. The proposed solution uses various ML classifiers, with a focus on **Light Gradient Boosting Machine (LGBM)**, to detect and classify network intrusions based on the **DS2OS dataset**.

## 🚀 Features

- Detection of anomalous and normal traffic in IoT networks
- Comparison of multiple ML algorithms:  
  - Logistic Regression (LR)  
  - Random Forest (RF)  
  - LightGBM (LGBM)  
  - XGBoost (XGB)  
- Ensemble learning using majority voting
- Performance evaluation using:
  - Accuracy
  - ROC Curve
  - Confusion Matrix
  - Runtime

## 📊 Results

- **LGBM-based model (LGB-IDS)** achieved **99.5% accuracy**
- Improved time efficiency and significantly reduced false alarm rate
- Ensemble voting further enhanced the model's reliability

## 🛠️ Tech Stack

- Python
- Scikit-learn
- LightGBM
- XGBoost
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook / VS Code

## 📁 Dataset

- **Name**: [DS2OS Dataset](https://www.kaggle.com/datasets/libamariyam/ds2os-dataset) (Distributed Smart Space Orchestration System)  
- **Description**: Includes labeled network traffic for normal and anomalous behaviors  
- 

## 🧠 Model Training & Evaluation

1. Data Preprocessing:
   - Handling missing values
   - Feature selection & normalization
2. Training individual classifiers
3. Hyperparameter tuning
4. Evaluation using metrics (accuracy, confusion matrix, ROC curve)
5. Ensemble majority voting


