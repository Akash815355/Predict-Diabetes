# 🩺 Diabetes Prediction using KNN

## 📖 Project Overview
This project uses the **K-Nearest Neighbors (KNN) algorithm** to predict whether a person has **diabetes** based on medical diagnostic features.  
The dataset used is the **PIMA Indians Diabetes Dataset**, which contains health-related parameters such as glucose level, BMI, and blood pressure.

## 🚀 Features
✅ Predicts diabetes using **KNN (K-Nearest Neighbors)**  
✅ Preprocesses the dataset (handling missing values & scaling)  
✅ Evaluates the model using **Accuracy, F1 Score, and Confusion Matrix**  
✅ Saves the trained model using **Joblib**  
✅ Provides options for **Hyperparameter tuning**  

---

## 📊 Dataset Information
- **Source:** PIMA Indians Diabetes Dataset ([Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database))  
- **Number of samples:** 768  
- **Number of features:** 8  
- **Target variable:** `Outcome` (0 = No Diabetes, 1 = Diabetes)  

### **📌 Features:**
| Feature | Description |
|---------|------------|
| Pregnancies | Number of times pregnant |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure (mm Hg) |
| SkinThickness | Triceps skin fold thickness (mm) |
| Insulin | 2-Hour serum insulin (mu U/ml) |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age | Age in years |
| Outcome | (0 = No Diabetes, 1 = Diabetes) |

---

## 🛠 **Installation & Setup**
To run this project on your local machine, follow these steps:

### **1️⃣ Clone the Repository**
```bash
git clone [https://github.com/yourusername/diabetes-prediction-knn.git](https://github.com/Akash815355/Predict-Diabetes.git)
cd diabetes-prediction-knn
