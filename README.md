# 🩺 Diabetes Prediction using Decision Tree Classifier

This project is a Machine Learning based **Diabetes Prediction System** using a **Decision Tree Classifier**.  
It takes medical input features and predicts whether a patient is **Diabetic (Affected)** or **Non-Diabetic (Not Affected)**.

---

## 📌 Project Features
✅ Dataset upload in Google Colab  
✅ Data preprocessing (null values & duplicates)  
✅ Train-Test split (80% train, 20% test)  
✅ Model training using Decision Tree  
✅ Model evaluation using Accuracy Score  
✅ User input testing for real-time predictions  

---

## 📂 Dataset
- File: `diabetes.csv`
- Target column: `Outcome`

### Outcome Values
- `0` → Not Affected (No Diabetes)
- `1` → Affected (Diabetes)

---

## 🛠️ Tech Stack
- Python  
- Google Colab  
- NumPy  
- Pandas  
- Scikit-learn  

---

## ⚙️ Algorithm Used
### ✅ Decision Tree Classifier
A Decision Tree builds classification rules using branching conditions on feature values and predicts the diabetes outcome.

---

## 🔄 Workflow
1. Data Collection  
2. Data Preprocessing  
3. Feature Selection  
4. Model Training  
5. Model Evaluation  
6. Prediction / Testing  

---

## 📌 Steps Performed
### 1️⃣ Upload Dataset (Google Colab)
```python
from google.colab import files
files.upload()
