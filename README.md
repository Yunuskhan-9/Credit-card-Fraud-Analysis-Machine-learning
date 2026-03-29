# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using various machine learning algorithms. Due to the highly imbalanced nature of fraud datasets, special techniques like **SMOTE (Synthetic Minority Over-sampling Technique)** are used to improve model performance.

The goal is to build and compare multiple models to accurately classify transactions as **fraudulent** or **legitimate**.

---

## 📂 Dataset

The project uses two datasets:

* `fraudTrain.csv` – for training the models
* `fraudTest.csv` – for evaluating model performance

### Features include:

* Transaction details (amount, date, time)
* Customer information (gender, location)
* Merchant details
* Target variable: `is_fraud`

---

## ⚙️ Project Workflow

1. **Data Loading**
2. **Data Cleaning**

   * Removed irrelevant/sensitive columns
3. **Feature Engineering**

   * Extracted transaction hour from timestamp
4. **Encoding**

   * Converted categorical data into numeric using Label Encoding
5. **Handling Imbalance**

   * Applied SMOTE to balance fraud vs non-fraud classes
6. **Exploratory Data Analysis (EDA)**

   * Visualized fraud distribution and patterns
7. **Model Training**
8. **Model Evaluation & Comparison**

---

## 📊 Exploratory Data Analysis

* Fraud vs Non-Fraud distribution (highly imbalanced)
* Transaction amount analysis
* Fraud trends across gender
* Correlation heatmap

These visualizations help understand patterns and relationships in the dataset.

---

## 🤖 Machine Learning Models Used

* **Logistic Regression**
* **Decision Tree**
* **Random Forest**
* **Naive Bayes**

---

## 📈 Evaluation Metrics

Models are evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score

> ⚠️ F1 Score is especially important due to class imbalance.

---

## 🏆 Results

* Ensemble models like **Random Forest** generally perform the best.
* SMOTE significantly improves fraud detection capability.
* Feature engineering (e.g., transaction hour) enhances model performance.

---

## 🚀 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)

---

## 📌 Key Insights

* Fraud transactions are very rare compared to normal transactions.
* Balancing the dataset is crucial for accurate predictions.
* Machine learning models can effectively identify hidden fraud patterns.

---

## 📎 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ``
3. Run the notebook:
```bash
   jupyter notebook
## 📚 Future Improvements

* Use Deep Learning models (ANN, LSTM)
* Deploy model using Flask/Streamlit
* Real-time fraud detection system
* Hyperparameter tuning for better accuracy


## ⭐ If you like this project

Give it a star ⭐ and feel free to contribute!

