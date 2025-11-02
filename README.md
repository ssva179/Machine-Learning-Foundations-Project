# Machine-Learning-Foundations-Project

This project aims to build a machine learning classifier to predict whether an individual has completed 12 or fewer years of education based on U.S. Census demographic data. Accurately predicting education level can support initiatives around resource allocation, social equity, and educational planning.

## 📌 Problem Statement
Given a set of demographic and socioeconomic features from the U.S. Census dataset, the goal is to predict whether a person has attained at most 12 years of education. This is a binary classification problem, tackled using supervised machine learning methods.

## 🧠 Why This Is Important
Education is a key determinant of income, job opportunities, and access to social services. A predictive model like this can help nonprofits and researchers identify communities in need
and better aim their efforts. 

## ⚙️ Methods and Approach
- Cleaned and preprocessed Census data (handled missing values and irrelevant features).  
- One-hot encoded categorical features and defined a binary target (`education_binary`).  
- Trained and tuned a **Random Forest Classifier** using `GridSearchCV` for hyperparameter optimization.  
- Evaluated performance using accuracy and confusion matrices.  

**Result:** Achieved ~80% accuracy after tuning hyperparameters.

---

## 🛠️ Tech Stack
- Python (pandas, numpy, matplotlib, seaborn)  
- scikit-learn (RandomForestClassifier, GridSearchCV)  
- Jupyter Notebook  

---

## 📈 Sample Output
