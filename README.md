# Exploratory Data Analysis (EDA) of COVID-19 Symptoms Dataset  

## 📌 Project Overview  
This project focuses on performing **Exploratory Data Analysis (EDA)** on a COVID-19 dataset.  
The goal is to explore patterns, visualize distributions, and identify key factors associated with COVID-19 outcomes.  

Unlike a full machine learning pipeline, this project is kept **EDA-only** to highlight analytical and visualization skills.  

---

## 📊 Dataset  
The dataset contains patient-level information such as:  
- **Demographics** – Age, Gender  
- **Symptoms** – Cough, Fever, Sore throat, Shortness of breath, Headache  
- **Contact history** – Known contact with COVID-positive case  
- **Target variable** – COVID test result (Positive/Negative)  

---

## 🔍 Analysis Performed  
1. **Data Cleaning & Overview**  
   - Handled missing values and inconsistencies  
   - Checked data types and summary statistics  

2. **Univariate Analysis**  
   - Distribution of symptoms (Yes/No counts)  
   - Gender-based distributions  
   - Age group frequencies  

3. **Bivariate Analysis**  
   - Symptom occurrence vs COVID outcome  
   - Gender vs COVID outcome  
   - Age trends in COVID-positive cases  

4. **Multivariate Analysis**  
   - Combined patterns of symptoms with COVID status  
   - Correlation heatmap of numerical features  

---

## 📈 Visualizations  
- Countplots and bar charts for categorical variables  
- Histograms and boxplots for numerical variables  
- Grouped visualizations comparing COVID outcomes across features  
- Interactive Plotly subplots for multi-symptom analysis  

---

## ✅ Key Insights  
- **Fever and cough** are the most significant symptoms linked with positive COVID test results.  
- **Shortness of breath** and **sore throat** also show moderate correlation with COVID positivity.  
- **Gender** does not show a very strong correlation, but slight differences exist.  
- **Older patients (60+)** are more likely to test positive compared to younger groups.  
- Contact with a confirmed case strongly increases the likelihood of testing positive.  

---

## 📝 Conclusion  
From the exploratory analysis, the dataset reveals several important trends:  
- Certain symptoms (fever, cough, breathing difficulties) are highly indicative of COVID-19.  
- Demographic variables such as **age** play an important role in infection likelihood.  
- Contact history is a strong predictor of COVID outcomes.  

This project demonstrates how **EDA can uncover hidden patterns** and guide further steps such as feature engineering and predictive modeling.  

---

## 🚀 Future Scope  
- Apply machine learning models (e.g., Logistic Regression, Decision Trees) for prediction.  
- Perform advanced feature engineering for symptom combinations.  
- Explore time-series trends if timestamped data is available.  

---

