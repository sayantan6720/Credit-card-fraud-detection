# 💳 Credit Card Fraud Detection

This project explores and analyzes anonymized credit card transaction data to detect fraudulent activity. It tackles the challenges of class imbalance through a range of resampling techniques and prepares the data for future machine learning model development.

---

## 📊 Overview

Credit card fraud detection poses unique challenges due to the heavily imbalanced nature of the data. This notebook focuses on:

- Exploratory Data Analysis (EDA)
- Feature scaling and normalization
- Handling class imbalance with **SMOTE**, **Random Undersampling**, and **SMOTEENN**
- Train-test split and stratification
- Laying the groundwork for machine learning classification

---

## 🧰 Tools & Libraries Used

### 📚 Data Manipulation & Visualization
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

### ⚙️ Preprocessing & Transformation
- **Scikit-learn (StandardScaler, train_test_split, metrics)**
- **SciPy (Box-Cox transformations)**

### 🔄 Imbalanced Learning
- **Imbalanced-learn (SMOTE, RandomUnderSampler, SMOTEENN)**

### 🤖 Deep Learning Framework
- **TensorFlow / Keras**

### 🖥️ Others
- **Pylab (rcParams for plotting)**
- **Termcolor (terminal output styling)**

---

## 🔍 Techniques Applied

- **Standardization**: Applied to the 'Amount' feature to normalize scale.
- **Box-Cox Normalization**: To reduce skewness in features.
- **Stratified Splitting**: Ensures class distribution is preserved in train/test splits.
- **Resampling**:
  - `SMOTE` for synthetic oversampling
  - `Random Undersampling` to reduce the majority class
  - `SMOTEENN`, a hybrid approach to balance the dataset

---

## 🧠 Next Steps

While this notebook primarily focuses on data exploration and preprocessing, next iterations may include:

- Training classifiers (Logistic Regression, Random Forest, Neural Networks)
- Evaluating model performance (ROC AUC, F1 Score, Confusion Matrix)
- Incorporating XAI techniques like SHAP or LIME for interpretability

---

## 📂 Dataset

This project uses the [Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) from Kaggle, which contains anonymized transactions by European cardholders in 2013.

---

## 👨‍💻 Author

**Sayantan Datta**  
[GitHub](https://github.com/sayantan6720) | [LinkedIn](https://www.linkedin.com/in/sayantan-datta/)

---

> ⚠️ _Note: This project is for educational and research purposes only._
