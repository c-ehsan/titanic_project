# 🚢 Titanic Survival Prediction

This project is based on the famous [Titanic dataset](https://www.kaggle.com/c/titanic) and aims to predict whether a passenger survived or not using **Machine Learning**.

---

## 📌 Project Description
The Titanic dataset contains information about passengers such as age, sex, passenger class, number of siblings/spouses aboard, and more.  
The goal is to build a classification model that predicts **Survived (1)** or **Died (0)**.

---

## ⚙️ Steps in the Project
1. **Data Cleaning**  
   - Handling missing values (e.g., Age, Embarked).  
   - Converting categorical values like `Sex` into numerical format.  
   - Feature selection (Age, Sex, Pclass, SibSp, Fare).  

2. **Data Splitting**  
   - Train/Test split (80% training, 20% testing).  

3. **Model Training**  
   - Logistic Regression / Random Forest (or other classifiers).  

4. **Evaluation**  
   - Accuracy score.  
   - F1-score.  
   - Confusion Matrix.  
   - Classification Report.  

---

## 📊 Results
- **Accuracy:** ~78%  
- **F1-Score:** ~76%  
- Confusion Matrix and heatmap visualization for better understanding.  

---

## 🛠️ Technologies Used
- Python 🐍  
- Pandas & NumPy (Data Processing)  
- Scikit-learn (Machine Learning)  
- Matplotlib & Seaborn (Visualization)  

---

## 📂 Files in Repository
- `titanic.ipynb` → Main notebook with full analysis and model building.  
- `README.md` → Project description (this file).  
- `requirements.txt` → Required libraries.  

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/YourUsername/titanic-prediction.git
