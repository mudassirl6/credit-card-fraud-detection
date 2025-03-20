# Credit Card Fraud Detection 🚀

This project detects fraudulent credit card transactions using **machine learning**.  
It utilizes **XGBoost** and **SMOTE** for handling class imbalance.

---

## 📌 **Project Overview**
- Dataset: **Credit Card Fraud Detection** ([Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud))  
- **Goal**: Identify fraudulent transactions while minimizing false positives.  
- **Model**: XGBoost Classifier  
- **Preprocessing**:
  - Standardized `Amount` and `Time`
  - Used **SMOTE** for handling **class imbalance**
  - Split data into **training & testing** sets  

---

## 📂 **Project Structure**
📂 CREDIT_CARD_FRAUD_DETECTION/
│── creditcard.csv        # Dataset containing transaction data
│── creditcard.ipynb      # Jupyter Notebook for training & evaluation
│── fraud_model.pkl       # Saved trained XGBoost model
│── readme.md             # Project documentation
│── requirements.txt      # Dependencies for setting up the environment

---

import kagglehub

# Download the latest version of the dataset
path = kagglehub.dataset_download("mlg-ulb/creditcardfraud")

print("Path to dataset files:", path)

### **Next Steps**
✅ **Ensure `creditcard.ipynb` includes the model training and evaluation process.**  
✅ **Confirm `fraud_model.pkl` is properly saved and loaded in `creditcard.ipynb`.**  
✅ **Check `requirements.txt` has all necessary dependencies (pandas, scikit-learn, XGBoost, etc.).**  

---

## 🚀 **How to Run the Project**

### 1️⃣ **Install Dependencies**
Make sure you have Python installed. Then, install required libraries:
```sh
pip install -r requirements.txt

jupyter notebook


📌 About the Project

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset contains transaction details, and the model is trained to classify transactions as fraudulent or legitimate.


🛠 Technologies Used
	•	Python
	•	Pandas
	•	Scikit-learn
	•	XGBoost
	•	Jupyter Notebook
