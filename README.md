# Explainable AI Techniques on Titanic Dataset

---

## 1. Project Title

**Implementing Explainable AI Techniques in Machine Learning Models using Titanic Dataset**

---

## 2. Objective

The objective of this project is to understand the importance of transparency and interpretability in machine learning models. This project demonstrates how Explainable AI (XAI) techniques can be used to analyze and visualize model decisions, improve trust, detect bias, and support debugging.

---

## 3. Problem Statement

Traditional machine learning models often act as black boxes, making it difficult to understand how predictions are made. This project addresses this issue by applying explainability techniques to interpret a classification model trained on the Titanic dataset.

The goal is to predict whether a passenger survived based on features such as age, gender, and passenger class.

---

## 4. Dataset

The Titanic dataset contains information about passengers aboard the Titanic ship.

### Key Features:
- Age  
- Sex  
- Pclass (Passenger Class)  
- Fare  
- Embarked  
- SibSp and Parch  

### Target Variable:
- **Survived (0 = No, 1 = Yes)**

---

## 5. Methodology

### Step 1: Data Preprocessing
- Handling missing values  
- Dropping irrelevant columns  
- Encoding categorical variables using one-hot encoding  
- Splitting dataset into training and testing sets  

---

### Step 2: Model Implementation
- Model used: **Random Forest Classifier**  
- Evaluation metrics:
  - Accuracy  
  - Classification Report  
  - Confusion Matrix  

---

### Step 3: Explainable AI Techniques

#### Global Explanations:
- Feature Importance  
- Permutation Importance  
- SHAP Summary Plot  

#### Local Explanations:
- SHAP Waterfall Plot  
- LIME Explanation  

---

### Step 4: Visualization and Analysis
- Survival distribution analysis  
- Feature importance visualization  
- SHAP plots (global and local)  
- Correlation heatmap  
- Bias and fairness analysis  

---

## 6. Tools and Libraries Used

### Programming Language:
- Python  

### Libraries:
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- SHAP  
- LIME  

---

## 7. Key Findings

- Gender, fare, and passenger class are the most influential features  
- Female passengers had higher survival probability  
- Higher ticket fare is associated with higher survival chances  
- The model reflects historical bias present in the dataset  
- SHAP and LIME provide consistent explanations  

---

## 8. Bias and Fairness

The model shows bias toward female passengers and higher-class individuals. While this reflects real-world patterns in the dataset, it highlights fairness concerns in machine learning systems.

Explainable AI helps identify and understand such biases.

---

## 9. Limitations

- Model is trained on historical data and may not generalize well  
- SHAP computations can be computationally expensive  
- LIME provides approximate explanations  
- Dataset contains inherent bias  

---

## 10. Conclusion

This project demonstrates how Explainable AI techniques improve the interpretability of machine learning models. SHAP and LIME provide valuable insights into model behavior, helping identify important features and biases.

Explainable AI enhances transparency, trust, and reliability in machine learning systems.

---

## 11. How to Run the Project

1. Open the Jupyter Notebook  
2. Ensure the dataset file is in the same directory  
3. Install required libraries:

```bash
pip install shap lime seaborn scikit-learn
