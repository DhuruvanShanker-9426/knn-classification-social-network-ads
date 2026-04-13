# 🧠 Social Network Ads Purchase Prediction using K-Nearest Neighbors

---

## 📌 Project Overview

This project demonstrates the implementation of a **classification model** using the K-Nearest Neighbors algorithm on the Social Network Ads dataset.

The objective is to predict whether a user will purchase a product based on features like age and estimated salary.

---

## 🎯 Objectives

* Understand the working of KNN algorithm
* Perform data preprocessing and scaling
* Train and evaluate a classification model
* Find the optimal K value
* Interpret model performance using evaluation metrics

---

## 📂 Dataset

* Dataset: Social Network Ads (from Kaggle)
* Features:

  * Age
  * Estimated Salary
* Target:

  * Purchased (0 or 1)

---

## 🛠️ Tools & Libraries Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🔍 Exploratory Data Analysis (EDA)

### 📊 Visualizations Used:

* Pairplot (relationship between features)

<img src="https://i.postimg.cc/NjBJDH0L/pair-plot.png" width=600>

* Countplot (target distribution)

<img src="https://i.postimg.cc/BnSpHfhm/count-plot.png" width=600>

---

## ⚙️ Model Building

### Steps:

1. Split data into training and testing sets
2. Applied **Standardization** using `StandardScaler`
3. Trained KNN model with different K values
4. Selected optimal K based on performance

---

## 📈 Model Evaluation

### 📊 Metrics Used:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

### 🔑 Key Insight:

* K values (3, 5, 7, 9) performed similarly
* **K = 5** selected as optimal for better balance between bias and variance

---

## 🔥 Results

* Model achieved strong performance across all evaluation metrics
* Proper scaling significantly improved KNN performance
* The model effectively classifies users based on given features

---

## 📌 Key Learnings

* Importance of **feature scaling in KNN**
* Understanding how K value affects model performance
* Evaluating models using multiple metrics (not just accuracy)
* Hands-on experience with a complete ML workflow

---

## 🚀 Future Improvements

* Try other algorithms (Logistic Regression, SVM)
* Perform cross-validation
* Visualize decision boundary
* Hyperparameter tuning using GridSearchCV

---

## 📌 Conclusion

This project helped build a strong foundation in **classification algorithms and model evaluation**, especially using KNN.