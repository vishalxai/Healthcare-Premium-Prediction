# 🩺 Health Insurance Cost Predictor
[![Streamlit](https://img.shields.io/badge/Streamlit-App-red)](https://health-insurance-cost-predictorxai.streamlit.app)
[![Python](https://img.shields.io/badge/Python-3.13-blue)]()
[![License](https://img.shields.io/badge/License-MIT-green)]()
A **Machine Learning web application** built with **Streamlit**, **Python**, and **Scikit-learn** that predicts annual health insurance premium amounts based on user details such as age, gender, income, BMI, and medical history.

---

## 🚀 Live Demo  
👉 [Open App on Streamlit](https://health-insurance-cost-predictorxai.streamlit.app)

---

## 📸 App Preview
| App Screenshot 1 | App Screenshot 2 |
|------------------|------------------|
![App Screenshot 1](screenshots/health_insurance_cost_predictor.png)
![App Screenshot 2](screenshots/Health_insurance_cost_predictor2.png)
---

## 🧠 Features
- Predicts **health insurance premium** using trained regression models  
- User-friendly **Streamlit** interface  
- Real-time predictions with intuitive input sliders and dropdowns  
- Supports multiple attributes:
  - Age  
  - Gender  
  - Income Level  
  - Employment Status  
  - BMI Category  
  - Smoking Habit  
  - Medical History  
  - Region  
  - Insurance Plan  

---

## 🧩 Tech Stack
| Component | Technology |
|------------|-------------|
| **Frontend** | Streamlit |
| **Backend/ML** | Python, scikit-learn, pandas, numpy, joblib |
| **Modeling** | Linear Regression, Ridge, Lasso, XGBoost |
| **Deployment** | Streamlit Cloud |

---

## 📂 Project Structure
Healthcare-Premium-Prediction/
│
├── artifacts/                     # Trained models and scalers
├── main.py                        # Streamlit app entry point
├── prediction_helper.py           # Model loading and prediction logic
├── requirements.txt               # Dependencies
├── LICENSE                        # Project license
└── screenshort/                   # Screenshots for README

---

## ⚙️ Installation and Running Locally
Follow these steps to run the project on your machine:

```bash
# Clone this repository
git clone https://github.com/vishalxai/Healthcare-Premium-Prediction.git

# Navigate into the folder
cd Healthcare-Premium-Prediction

# Install required dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run main.py
```
🧾 Model Details

The regression model predicts annual insurance premium amounts based on:
	•	Demographics: Age, Gender, Region
	•	Socioeconomic Factors: Income, Employment, Dependents
	•	Lifestyle: Smoking, BMI, Medical History
	•	Policy Plan: Bronze / Silver / Gold

All trained models and scalers are stored inside the artifacts/ folder.

🧑‍💻 Author

Vishal Singh
📍 Bangalore, India
🔗 Streamlit App
💻 GitHub Profile
🪪 License

This project is licensed under the MIT License — free for use, modification, and distribution.
