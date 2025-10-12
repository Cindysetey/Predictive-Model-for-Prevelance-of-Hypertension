# Predictive Model for Prevalence of Hypertension

This project uses machine learning to predict the **probability of hypertension** and classify the **clinical blood pressure stage** based on user inputs.

## Features
- Secure password-protected access
- Predictive model trained using Random Forest
- Clinical risk classification based on systolic & diastolic BP
- Auto-logging of predictions
- Streamlit web app interface

## Risk Classification Criteria
| Category | Systolic (mmHg) | Diastolic (mmHg) |
|-----------|-----------------|------------------|
| **Normal** | <120 | <80 |
| **Elevated** | 120–129 | <80 |
| **Stage 1 Hypertension** | 130–139 | 80–89 |
| **Stage 2 Hypertension** | ≥140 | ≥90 |

## Model Output
The system outputs both:
1. The **predicted probability (%)** from the machine learning model  
2. The **clinical blood pressure stage** based on user input

## 🏃 How to Run Locally
```bash
pip install -r requirements.txt
streamlit run hypertension_app.py
