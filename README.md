# ❤️ Heart Disease Prediction Model

This project is a **Machine Learning-based web app** built using **Streamlit**, designed to predict whether a person is at risk of **Heart Disease** based on clinical parameters.  
The project compares multiple ML algorithms and deploys the **best-performing KNN model** for prediction.

---

## 🚀 Project Overview

The objective is to predict the likelihood of **Heart Disease** based on health indicators such as age, blood pressure, cholesterol, ECG results, and more.  

### 📋 Dataset Features
| Column | Description |
|--------|--------------|
| Age | Age of the patient |
| Sex | Gender (M/F) |
| ChestPainType | Type of chest pain experienced |
| RestingBP | Resting blood pressure (mm Hg) |
| Cholesterol | Serum cholesterol (mg/dl) |
| FastingBS | Fasting blood sugar (1 if >120 mg/dl, else 0) |
| RestingECG | Resting electrocardiographic results |
| MaxHR | Maximum heart rate achieved |
| ExerciseAngina | Exercise-induced angina (Y/N) |
| Oldpeak | ST depression induced by exercise |
| ST_Slope | Slope of the peak exercise ST segment |
| HeartDisease | Target variable (1 = presence, 0 = absence) |

---

## 🧠 Model Building

The following **classification algorithms** were trained and evaluated:
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  
- Decision Tree  
- Support Vector Machine (RBF Kernel)

After performance comparison, **KNN** achieved the **highest accuracy (~88%)** and was selected for deployment.

---

## 📊 Model Performance

| Model | Accuracy |
|--------|-----------|
| Logistic Regression | 87% |
| KNN | **88%** |
| Naive Bayes | 86% |
| Decision Tree | 76% |
| SVM (RBF) | 86% |

✅ **KNN** was used in the final Streamlit app.

---

## 🧰 Tech Stack

| Component | Technology |
|------------|-------------|
| Language | Python |
| Libraries | scikit-learn, pandas, numpy, joblib |
| Frontend | Streamlit |
| IDE | Jupyter Notebook |

---

## 📂 Project Structure
├── app.py # Streamlit web app
├── ML_Model.ipynb # Model training and evaluation
├── KNN_heart.pkl # Best model (KNN)
