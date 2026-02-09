# 🌸 Iris Flower Classification using KNN

This project implements a **K-Nearest Neighbors (KNN)** machine learning model to classify Iris flower species.  
The dataset is stored in a **SQLite database** and the entire workflow is implemented in **Python**.

---

## 📌 Project Overview

The goal of this project is to predict the species of an Iris flower based on its physical measurements using a distance-based classification algorithm.

**Classes predicted:**
- Iris-setosa  
- Iris-versicolor  
- Iris-virginica  

---

## 📊 Dataset Information

- **Dataset:** Iris Dataset  
- **Source:** UCI Machine Learning Repository  
- **Number of Samples:** 150  
- **Features:**
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- **Target Variable:** Species

---

## 🗃️ Database Used

- **Type:** SQLite  
- **File:** `irisdatabase.sqlite`  
- **Table Name:** `iris`

---

## 🧠 Algorithm Used

### K-Nearest Neighbors (KNN)
- Distance-based supervised learning algorithm
- Classifies data based on majority voting of nearest neighbors
- Feature scaling applied using `StandardScaler`

---

## ⚙️ Technologies & Libraries

- Python  
- Pandas  
- SQLite3  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## 📈 Model Performance

- **Accuracy:** 100%  
- **Precision:** 1.00  
- **Recall:** 1.00  
- **F1-Score:** 1.00  

The model perfectly classified all test samples, which is expected for the well-separated Iris dataset.

---

## 📉 Visualization

- Pair plots created using Seaborn
- Visual representation of feature relationships
- Clear class separation observed

##Results


The KNN model successfully classifies Iris flower species with perfect accuracy on the test dataset, demonstrating the effectiveness of distance-based classification on small, clean datasets.
