# 🌍 Earthquake Damage Prediction using Machine Learning

## 📌 Project Overview
This project is an end-to-end machine learning solution designed to predict the severity of building damage caused by earthquakes. By analyzing structural characteristics, construction materials, and geographic factors, the model classifies buildings into Low, Medium, and High damage categories, enabling data-driven disaster risk assessment and structural safety planning.

---

## 🎯 Problem Statement
Earthquakes often result in severe structural damage, especially in regions with older buildings and weak construction materials. Traditional damage assessment methods are manual, time-consuming, and inconsistent. This project aims to automate the prediction of earthquake-induced building damage using machine learning techniques.

---

## 🚀 Objectives
- Perform detailed Exploratory Data Analysis (EDA)
- Understand the impact of structural, material, and geographic features
- Build a robust machine learning model for damage prediction
- Identify key factors influencing earthquake damage
- Provide actionable insights for safer construction practices

---

## 📊 Dataset Description
- Total Records: 260,601 buildings
- Features: 39 (numerical and categorical)
- Target Variable: `damage_grade`
  - 1 – Low Damage
  - 2 – Medium Damage
  - 3 – High Damage

Feature categories include geographic location, building age, number of floors, height and area percentage, foundation type, roof type, and construction materials such as mud mortar, adobe, timber, and reinforced concrete.

---

## 🔍 Exploratory Data Analysis (EDA)
- No missing values found in the dataset
- Damage Grade 2 is the most frequent class
- Older buildings show higher damage severity
- Taller buildings and weak construction materials are more vulnerable
- Geographic location plays a significant role in damage patterns

---

## 🧹 Data Preprocessing
- Numerical features handled using median imputation and standard scaling
- Categorical features processed using frequent value imputation and one-hot encoding
- Data split into 80% training and 20% testing with stratification
- Preprocessing implemented using a unified Scikit-learn pipeline

---

## 🤖 Model Development
- Model Used: Random Forest Classifier
- Reason: Handles mixed data types, captures non-linear relationships, and reduces overfitting

### Model Performance
- Accuracy: 71.8%
- Balanced Accuracy: 63.5%
- Cohen’s Kappa Score: 0.468

The model performs well across all damage categories and handles class imbalance effectively.

---

## ⭐ Feature Importance
Top factors influencing earthquake damage:
- Geographic location (geo levels)
- Building age
- Height and area percentage
- Number of floors and families
- Foundation type
- Construction materials (mud, adobe, timber)

---

## 📌 Recommendations
- Retrofit older and structurally weak buildings
- Promote engineered and reinforced construction materials
- Strengthen foundations in high-risk zones
- Apply region-specific building safety standards
- Limit building height in earthquake-prone areas

---

## 🏁 Conclusion
This project demonstrates a complete machine learning workflow, from data analysis to model deployment-ready insights. By leveraging real-world data and ensemble learning techniques, the system provides accurate damage predictions and valuable insights that can support disaster preparedness, risk mitigation, and safer infrastructure planning.

---

## 👩‍💻 Author
**Haritha K**  
DATA-DRIVEN PROFESSIONAL  
Focused on real-world data-driven problem solving
