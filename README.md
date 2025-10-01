# 🧠 Breast Cancer Prediction using Machine Learning

## 📘 Overview
This project marks my **first unguided machine learning project**, where I independently built a predictive model to classify breast cancer tumors as **Malignant (M)** or **Benign (B)**.

The main goal was to understand and implement the **end-to-end ML workflow** — from data import and preprocessing to model training, evaluation, and selection — without any guided tutorial. 

---

## 📂 Dataset
The dataset was collected from **Kaggle**:  
 

It contains features extracted from digitized images of breast masses, including:
- Mean radius  
- Texture  
- Smoothness  
- Compactness  
- Concavity  
- Symmetry  
- Fractal dimension  

**Target Variable:** `diagnosis`  
- **M** → Malignant  
- **B** → Benign  

---

## ⚙️ Project Workflow

### 🔹 Step 1: Data Preprocessing
- Imported dataset using **pandas**  
- Checked for missing values and data types  
- Encoded categorical variable `diagnosis` (M/B) into numeric using **LabelEncoder**

### 🔹 Step 2: Exploratory Data Analysis (EDA)
- Visualized data distribution using **Seaborn** and **Matplotlib**  
- Checked balance of target classes  
- Explored relationships between features and diagnosis  

### 🔹 Step 3: Model Building
Tested multiple machine learning algorithms:
- Linear Regression  
- Lasso Regression  
- Decision Tree Regressor  
- **Logistic Regression** ✅  

### 🔹 Step 4: Model Evaluation
- Split dataset: **80% Training / 20% Testing**  
- Used **GridSearchCV** and **Cross-Validation** for hyperparameter tuning  
- Evaluated each model based on accuracy and consistency  

---

## 🎯 Results
| Model | Accuracy |
|-------|-----------|
| Linear Regression | ~73.9% |
| Lasso Regression | ~50.4% |
| Decision Tree Regressor | ~71.1% |
| **Logistic Regression** | **95.4% ✅** |

🧠 **Best Model:** Logistic Regression  
📊 **Accuracy:** 95.4%  
🔁 **Cross-Validation:** Stable across multiple splits  

---

## 🧰 Tools & Libraries
- **Language:** Python  
- **Libraries Used:**  
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  

---

## 📈 Key Learnings
- Converting categorical labels using **LabelEncoder**  
- Performing EDA to understand feature distributions  
- Building multiple ML models and comparing their performance  
- Applying **GridSearchCV** for hyperparameter tuning  
- Evaluating models with **cross-validation**

---

## 🚀 Future Work
- Try other classification models: **Random Forest**, **SVM**, **XGBoost**  
- Implement **feature importance analysis**  
- Deploy the model as a **Streamlit web app** for predictions  

---

 
