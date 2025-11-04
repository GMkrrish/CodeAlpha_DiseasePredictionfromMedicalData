# CodeAlpha_DiseasePredictionfromMedicalData


# 🧠 Disease Prediction from Medical Data  
### CodeAlpha Machine Learning Internship – Task 4

---

## 🎯 Objective
Predict the **possibility of diseases** (like Heart Disease or Diabetes) using structured medical datasets.  
The goal is to apply various **classification algorithms** and compare their effectiveness in identifying disease risk based on patient data.

---

## 🧩 Approach

1. **Dataset Used**
   - **Heart Disease Dataset** – UCI ML Repository  
   - **Diabetes Dataset** – Pima Indians Diabetes Dataset  
   - Each dataset includes features such as *age, blood pressure, cholesterol, glucose, BMI,* and other clinical indicators.

2. **Data Processing**
   - Missing value handling using median imputation  
   - Label encoding for categorical features  
   - Feature scaling using `StandardScaler`  
   - Stratified train–test split (80/20)

3. **Algorithms Implemented**
   - Logistic Regression  
   - Support Vector Machine (SVM)  
   - Random Forest Classifier  
   - Gradient Boosting Classifier  
   - XGBoost Classifier  

4. **Evaluation Metrics**
   - Accuracy  
   - Precision  
   - Recall  
   - F1-Score  
   - ROC-AUC  
   - 5-Fold Cross-Validation

5. **Visualization**
   - Feature correlation heatmaps  
   - Target class distributions  
   - ROC curves for each model  
   - Confusion matrices for best-performing models  

---

## ⚙️ Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/GMKrrish/CodeAlpha_DiseasePrediction.git
cd CodeAlpha_DiseasePrediction
