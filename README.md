# 💳 Credit Card Fraud Detection using Random Forest

## 📌 Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques. We use the **Random Forest Algorithm** along with **Hyperparameter Tuning** to improve model performance and accurately identify fraud cases.

---

## 🎯 Objective

* Detect fraudulent transactions from a highly imbalanced dataset
* Maximize **Recall** to catch maximum fraud cases
* Maintain a balance between Precision and Recall

---

## 🧠 Technologies Used
* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* optuna
---

## 📂 Dataset

* The dataset contains anonymized credit card transactions
* Features are numerical (V1, V2, ..., V28)
* Includes:

  * `Time`
  * `Amount`
  * `Class` (0 = Normal, 1 = Fraud)

---

## ⚙️ Project Workflow

### 1. Data Preprocessing

* Handle missing values (if any)
* Handle imbalanced data using:
  * Oversampling (e.g., SMOTE)
---

### 2. Exploratory Data Analysis (EDA)

* Distribution of fraud vs normal transactions
* Correlation heatmap
* Transaction amount analysis
* Fraud time analysis
---

### 3. Model Building

We used the **Random Forest Classifier**:
* Ensemble learning method
* Handles non-linear relationships
* Robust to overfitting

---

### 4. Hyperparameter Tuning
We applied **Optuna** to optimize:

* `n_estimators`
* `max_depth`
* `random_state`
* `bootstrap`
---

### 5. Model Evaluation

Key metrics used:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score

⚠️ **Important:**
Recall is prioritized because missing fraud cases is costly.
---

## 📊 Results
* Improved Recall after tuning
* Better balance between Precision & Recall
* Reduced False Negatives
---

## 📈 Visualization
* Precision-Recall Curve
* ROC Curve
* Confusion Matrix
---

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/Sourav1000888/Credit-card-fraud-detection

# Navigate to project folder
cd fraud-detection
---

## 📁 Project Structure

```
fraud-detection/
│── dataset/
├── creditcard.csv
│── notebooks/
│   ├── Credit card fraud detection.ipynb
│── requirements.txt
│── README.md
```
---

## 🔍 Key Insights

* Fraud datasets are highly imbalanced
* Random Forest performs well without heavy feature engineering
* Hyperparameter tuning significantly improves recall
---

