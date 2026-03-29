# 🏦 Loan Prediction Machine Learning Model

## 📌 Overview

This project focuses on predicting loan approval status using Machine Learning techniques. The model analyzes applicant data and determines whether a loan should be approved or not based on various features.

The final model achieved an accuracy of **88%**, improved from an initial **84%** after optimization.

---

## 🧠 Key Features

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature engineering
* Model training and comparison
* Hyperparameter tuning for performance improvement

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries:**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
  * Scikit-learn

---

## 📊 Exploratory Data Analysis

* Performed data visualization using Seaborn and Matplotlib
* Analyzed feature relationships and patterns
* Identified important variables affecting loan approval

```python
import seaborn as sns
import matplotlib.pyplot as plt
import numpy as np
```

---

## ⚙️ Feature Engineering

* Converted categorical data using Label Encoding
* Applied feature scaling using StandardScaler

```python
from sklearn import preprocessing
labelencoder = preprocessing.LabelEncoder()

from sklearn.preprocessing import StandardScaler
scaler = StandardScaler()
```

---

## 🤖 Models Used

* K-Nearest Neighbors (KNN)

* Support Vector Classifier (SVC)

* Logistic Regression

* Used Grid Search for hyperparameter tuning and model optimization

---

## 📈 Model Performance

* Initial Accuracy: **84%**
* Final Accuracy: **88%** ✅

---

## 🔍 Results

* Improved prediction accuracy through proper feature engineering
* Compared multiple algorithms to select the best model
* Built a reliable classification system for loan approval prediction

---

## 📂 Project Structure

```
├── data/
├── notebook.ipynb
├── model.pkl
├── README.md
```

---

## 🚀 How to Run

1. Clone the repository
2. Install required libraries using pip
3. Run the Jupyter Notebook or Python script

---

## 👨‍💻 Author

**Vinit Sharma**
GitHub: https://github.com/vinitsu899

---

## ⭐ Future Improvements

* Deploy model using Flask or Streamlit
* Improve accuracy with advanced algorithms
* Use larger and more diverse datasets

---

## 🙌 Conclusion

This project demonstrates practical implementation of Machine Learning techniques including data preprocessing, feature engineering, and model optimization to solve a real-world problem.
