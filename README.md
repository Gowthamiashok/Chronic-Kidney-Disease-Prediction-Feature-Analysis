#🩺 Chronic Kidney Disease Prediction & Feature Analysis

 - This project focuses on the detection of chronic kidney disease (CKD) based on clinical and laboratory features.
 - It explores the most important factors for CKD using machine learning and data analysis techniques.

---

## 🎯 Objective

  - Analyze clinical and lab data to predict CKD
  - Identify which patient features are most strongly associated with disease status
  - Visualize patterns and distributions of key variables

---

## 🗂 Dataset

  - 400 patient records, 26 features each
  - Clinical info: age, blood pressure, hypertension, diabetes, anemia, etc.
  - Lab tests: blood urea, serum creatinine, haemoglobin, WBC/RBC counts, electrolytes, etc.
  - Outcome label: ckd or notckd

---

## 🔄 Data Processing

| Step | Description |
|------|-------------|
| Import | Read CSV, set column names |
| Clean | Handle missing values and data types |
| Explore | View distributions, correlations, missingness |
| Feature Score | Calculate and rank features (statistical tests) |

---

## 📊 Feature Importance

Top features most associated with CKD:

  - WBC count
  - Blood glucose random
  - Blood urea
  - Serum creatinine
  - Packed cell volume
  - Albumin
  - Haemoglobin
  - Age
  - Sugar
  - Hypertension

These variables show the strongest statistical relationship with kidney disease status.

---

## 📌 Key Insights

  - Higher values in lab features like serum creatinine, blood urea, and WBC count are risk signals for CKD.
  - Low haemoglobin and packed cell volume are common in CKD patients.
  - Comorbid factors like hypertension and diabetes are more frequent in CKD.
  - Early detection is possible by focusing on these critical lab values and comorbidities.

---

## 🌱 Learning Outcomes

This project gave hands-on experience in:
 
  - Preprocessing mixed medical data
  - Handling missing and categorical features
  - Calculating and interpreting feature importance
  - Gaining clinical insights for disease detection

---

## 🙏 Acknowledgment

This analysis was conducted for academic learning and practice in healthcare analytics using open datasets.

---
