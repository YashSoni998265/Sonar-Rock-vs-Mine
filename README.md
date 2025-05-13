# 🎯 Sonar Rock vs Mine Prediction using Logistic Regression

This Deep Learning project aims to classify sonar signals as either **Rock** or **Mine** using the **Sonar Dataset**. The dataset contains 60 features based on the energy of sonar signals bounced off different objects. This binary classification problem is solved using **Logistic Regression**, and all essential steps including data preprocessing, model training, and evaluation have been covered.

> ✅ **Dataset is attached with this repository** for easy access and replication.

---

## 📂 Project Structure

```bash
Sonar-Rock-vs-Mine/
├── sonar.csv                # 📊 The sonar dataset (attached)
├── sonar_prediction.py     # 🧠 Model training and prediction code
├── README.md                # 📘 Project overview

🚀 Workflow
1. 📦 Importing the Dependencies
All necessary Python libraries like pandas, numpy, sklearn, and matplotlib are imported to perform data analysis, preprocessing, modeling, and evaluation.

2. 🧹 Data Collection and Preprocessing
Loaded the sonar dataset.

Converted labels from categorical to binary (R = Rock, M = Mine).

Normalized/Standardized the data as needed.

Split the dataset into training and testing sets (stratified sampling).

3. 🧠 Model Training
Used Logistic Regression from sklearn.linear_model to train on the sonar dataset. This simple yet effective algorithm is well-suited for binary classification tasks like this one.

4. 📊 Model Evaluation
Evaluated the model on both training and test data.

Calculated accuracy scores and printed classification results.

Visualized model performance (optional based on code).

5. 🔮 Making a Predictive System
Created a system that:

Accepts new input data,

Processes it,

Predicts whether the object is a Rock or a Mine based on sonar readings.

📌 Tech Stack
Python

NumPy

Pandas

Scikit-learn

Jupyter Notebook / Python script

📈 Accuracy
Dataset	Accuracy
Training Set	✅ 83.4%
Test Set	✅ 76.19%

📥 Dataset Info
Source: UCI Machine Learning Repository

Features: 60 numeric features per instance

Classes:

R → Rock

M → Mine

The dataset (sonar.csv) is provided in this repository for your convenience.

