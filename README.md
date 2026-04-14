# 🚀 Explainable AI on Titanic Dataset

---

## 🎯 Project Title
**Implementing Explainable AI Techniques in Machine Learning Models using Titanic Dataset**

---

## 📌 Objective
The objective of this project is to understand the importance of **transparency and interpretability** in machine learning models.  
This project demonstrates how **Explainable AI (XAI)** techniques help:
- 🔍 Understand model decisions  
- 🤝 Improve trust  
- ⚖️ Detect bias  
- 🛠️ Support debugging  

---

## ❓ Problem Statement
Traditional machine learning models often behave like **black boxes**, making it difficult to interpret predictions.  

This project addresses this issue by:
- Building a classification model  
- Applying XAI techniques  
- Explaining predictions clearly  

🎯 Goal: Predict whether a passenger **survived or not** using the Titanic dataset.

---

## 📊 Dataset Description

The Titanic dataset contains passenger details including demographic and socio-economic features.

### 🔑 Key Features:
- Age  
- Sex  
- Pclass (Passenger Class)  
- Fare  
- Embarked  
- SibSp and Parch  

### 🎯 Target Variable:
- **Survived (0 = No, 1 = Yes)**

---

## ⚙️ Methodology

### 🧹 Step 1: Data Preprocessing
- Handling missing values  
- Dropping irrelevant columns  
- One-hot encoding categorical variables  
- Train-test split  

---

### 🤖 Step 2: Model Implementation
- Model used: **Random Forest Classifier**
- Evaluation metrics:
  - Accuracy  
  - Classification Report  
  - Confusion Matrix  

---

### 🧠 Step 3: Explainable AI Techniques

#### 🌍 Global Explanations:
- Feature Importance  
- Permutation Importance  
- SHAP Summary Plot  

#### 🎯 Local Explanations:
- SHAP Waterfall Plot  
- LIME Explanation  

---

### 📈 Step 4: Visualization & Analysis
- Survival distribution  
- Feature importance plots  
- SHAP visualizations  
- Correlation heatmap  
- Bias and fairness analysis  

---

## 🛠️ Tools and Libraries

### 💻 Programming Language:
- Python  

### 📚 Libraries Used:
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- SHAP  
- LIME  

---

## 🔍 Key Findings

- 🚺 Gender is the most influential feature  
- 💰 Higher fare increases survival probability  
- 🛳️ Passenger class strongly affects survival  
- ⚠️ Model reflects historical bias  
- 🔁 SHAP and LIME provide consistent explanations  

---

## ⚖️ Bias and Fairness

The model shows bias toward:
- Female passengers  
- Higher-class passengers  

📌 While this reflects real-world data, it highlights **fairness concerns** in AI systems.  
XAI helps identify and understand such biases.

---

## ⚠️ Limitations

- Model trained on historical data  
- SHAP can be computationally expensive  
- LIME provides approximate explanations  
- Dataset contains inherent bias  

---

## ✅ Conclusion

This project demonstrates how **Explainable AI enhances transparency** in machine learning models.

✔ SHAP provides global insights  
✔ LIME explains individual predictions  
✔ Model decisions become interpretable  

➡️ XAI improves **trust, reliability, and understanding**

---

## ▶️ How to Run the Project

1. Open the Jupyter Notebook  
2. Ensure dataset is in the same directory  
3. Install required libraries:

```bash
pip install shap lime seaborn scikit-learn
