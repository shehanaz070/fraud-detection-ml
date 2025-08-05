# fraud-detection-ml
A machine learning project to detect fraudulent transactions using Random Forest
# 🕵️‍♀️ Fraud Detection using Machine Learning

This project uses a **Random Forest Classifier** to detect fraudulent financial transactions in a large dataset of over 6 million rows.  
It includes preprocessing, feature engineering, model training, evaluation, and visualization.

---

## 📁 Files Included

| File Name                | Description                              |
|--------------------------|------------------------------------------|
| `fraud_detection.ipynb`  | Jupyter Notebook with full project code  |
| `feature_importance.png` | Graph showing top features influencing fraud prediction |
| `requirements.txt`       | List of required Python libraries        |

---

## 📊 Technologies Used

- **Python**
- **Pandas** for data manipulation  
- **Seaborn & Matplotlib** for plotting  
- **Scikit-learn** for ML model training  
- **Jupyter Notebook**

---

## 🔎 About the Dataset

The dataset contains the following columns:
- `step`, `type`, `amount`, `nameOrig`, `oldbalanceOrg`, `newbalanceOrig`, etc.
- Target column: `isFraud`

No missing values and no duplicates are present in the data.

---

## 🧠 Model Used: Random Forest

A **Random Forest Classifier** was trained using:
- Balanced class weights
- 80/20 train-test split
- Stratified sampling for imbalanced data

📈 Evaluation Metrics:
- Confusion Matrix  
- Classification Report  
- ROC AUC Score  
- Feature Importance Graph

---

## 📷 Output Snapshot

![Feature Importance] (feature_importance.png)


## 🛠 How to Run This Project

1. Clone the repository  
   ```bash
   git clone https://github.com/shehanaz070/fraud-detection-ml.git

   cd fraud-detection-ml

2.pip install -r requirements.txt

