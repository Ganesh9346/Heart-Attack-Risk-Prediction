# Heart Attack Risk Prediction 💔🩺

## 📌 Project Overview

This project delves into the vital field of healthcare analytics and machine learning to predict the risk of heart attacks. By uncovering patterns within comprehensive patient health data, this initiative aims to empower medical professionals with a proactive tool for early risk assessment and personalized preventive care strategies.

---

## 📊 The Dataset

At the heart of this analysis is the `heart1.csv` dataset — a rich collection of patient health indicators. This dataset provides a multi-dimensional view of factors potentially influencing cardiac health.

**Key Features include:**

- Patient ID  
- Age  
- Sex  
- Cholesterol  
- Blood Pressure  
- Heart Rate  
- Diabetes  
- Family History  
- Smoking  
- Obesity  
- Alcohol Consumption  
- Exercise Hours Per Week  
- Diet  
- Previous Heart Problems  
- Medication Use  
- Stress Level  
- Sedentary Hours Per Day  
- Income  
- BMI  
- Triglycerides  
- Physical Activity Days Per Week  
- Sleep Hours Per Day  
- Country  
- Continent  
- Hemisphere  
- **Heart Attack Risk** (Target Variable)

---

## 💻 Methodology & Current Progress

This project follows a standard data science pipeline. The work completed so far (detailed in `Untitled15 (10).ipynb`) includes:

### ✅ Data Loading & Initial Inspection
- Loaded the `heart1.csv` dataset.
- Performed basic structural checks using `df.head()`, `df.info()`, and `df.shape`.

### ✅ Robust Data Cleaning
- Removed the redundant `Unnamed: 25` column (100% null).
- Verified absence of duplicate rows.

### ✅ Preliminary Outlier Analysis
- Used `df.describe()` and boxplots (e.g., for 'Cholesterol') to explore potential outliers.

### ✅ Initial Insights & Conceptual Framing
- Identified strong correlation between **Smoking** and **Heart Attack Risk**.
- Noted relationship between **Age** and **Smoking**.
- Highlighted the potential of ML to empower early detection and preventive strategies.

---

## 📈 Key Findings (Current Stage)

- **Smoking** is a significant, modifiable risk factor for heart attack.
- There's a notable correlation between **Age** and **Smoking**.
- Early data insights reveal the potential for personalized preventive healthcare through predictive modeling.

---

## 🚀 Future Enhancements

### 🔧 Data Preprocessing
- **Blood Pressure Transformation**: Convert from object to separate numerical fields (Systolic & Diastolic).
- **Categorical Encoding**: Apply One-Hot or Label Encoding to categorical features (e.g., Sex, Diet, Country).
- **Outlier Treatment**: Apply strategies like capping, transformation, or removal.
- **Feature Engineering & Selection**: Create informative features and select the most impactful ones.

### 🤖 Machine Learning Model Development
- **Data Splitting**: Train-test split.
- **Model Training**: Try models like Logistic Regression, Decision Trees, Random Forests, SVM, Gradient Boosting.
- **Hyperparameter Tuning**: Use GridSearchCV or RandomizedSearchCV.
- **Cross-Validation**: Apply k-fold validation for robust evaluation.

### 📊 Model Evaluation & Interpretation
- Use metrics like **Accuracy, Precision, Recall, F1-Score, ROC-AUC**.
- Display and interpret **feature importance**.
- Conduct deeper **Exploratory Data Analysis (EDA)** using box plots, bar charts, etc.

---

## 🛠️ Tools & Libraries

This project uses the following technologies:

- **Python** – Core programming language  
- **Pandas** – Data manipulation & analysis  
- **NumPy** – Numerical operations  
- **Matplotlib** – Basic visualization  
- **Seaborn** – Statistical plotting  
- **(Planned)** Scikit-learn – ML modeling and evaluation

---

## 📌 Final Note

This project is a step toward building impactful healthcare solutions using data. By identifying at-risk individuals early, we can support timely medical intervention and personalized health strategies — potentially saving lives. 💖
