# Hospital Readmission Prediction for Diabetes Patients
**Master's Project - University of Baghdad** **Author: Rusul Hayder Abd Zaid**

## 📌 Project Overview
This project aims to develop a predictive model to identify factors influencing hospital readmission for diabetes patients. Using the "Diabetes 130-US hospitals" dataset (1999–2008), the study focuses on clinical attributes to improve patient outcomes and hospital efficiency through AI-driven insights.

## 📊 Progress Log

### Week 1: Data Profiling & Initial Cleaning (Completed)
* **Environment Setup:** Configured Google Colab with Python, Pandas, and NumPy.
* **Data Auditing:** Analyzed 101,766 clinical records with 50 attributes.
* **Key Findings:** * Identified significant missingness in the `weight` attribute (**96.86% missing values**).
    * Determined that `weight` is statistically unreliable for this specific model.
* **Data Cleaning:**
    * Removed sparse and non-predictive features (`weight`, `encounter_id`, `patient_nbr`, `payer_code`).
    * Standardized missing values (coded as '?') by converting them to 'Unknown' for better categorical handling.
    * Verified the integrity of primary features: `race`, `gender`, and `age`.

## 🛠️ Technologies Used
* **Language:** Python
* **Libraries:** Pandas, NumPy
* **Environment:** Google Colab / GitHub Integration

---
*Note: This repository is updated weekly as part of the "Applied Modelling Extension" pathway.*
