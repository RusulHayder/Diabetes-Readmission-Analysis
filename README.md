# Clinical Prediction of Hospital Readmission in Diabetic Patients
**Author:** Rusul Hayder Abd Zaid  
**Academic Institution:** College of Artificial Intelligence, University of Baghdad  
**Specialization:** Biomedical Informatics & Bioinformatics

---

## 📌 Project Overview
This repository contains a machine learning pipeline designed to predict 3-class hospital readmission for diabetes patients. The project establishes a rigorous **Baseline** and explores **Advanced Ensemble Methods** to improve clinical decision-making.

## 🛠️ Methodology & Technical Stack
- **Data Balancing:** Applied **SMOTE** to handle the imbalance in the 3-class target variable.
- **Preprocessing:** Used `StandardScaler` for feature normalization and handled missing values.
- **Models Implemented:**
  - **Logistic Regression:** Established as a baseline ($Accuracy: 55.6\%$).
  - **Optimized Random Forest:** Achieved a higher **Macro F1-Score ($0.405$)** through Hyperparameter Tuning.
- **Tools:** Python (Scikit-Learn, Pandas, Seaborn), Google Colab, LaTeX for reporting.

## 📊 Key Findings
- Identified `num_lab_procedures` and `num_medications` as the top clinical predictors.
- The optimized Random Forest demonstrated better sensitivity towards high-risk patients (Readmission < 30 days) compared to the linear baseline.

## 🚀 How to Execute
1. Open the `.ipynb` file in this repository.
2. Click on the **"Open in Colab"** badge.
3. Upload the `diabetic_data.csv` when prompted or ensure the path is correctly set.
