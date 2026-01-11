# ❤️ CardioVascular – Heart Disease Prediction System

**CardioVascular** is a machine learning–powered web application developed as a **college project** by me and my team, with end-to-end implementation handled by me.  
The system predicts the **risk and type of heart disease** using clinical inputs, symptom analysis, and weighted logic, and generates a **visual and downloadable health report**.

---

## 🚀 Project Overview

Heart disease is one of the leading causes of death worldwide.  
CardioVascular aims to assist users by providing an **early, data-driven prediction system** that goes beyond a simple *yes/no* output.

The application:
- Predicts whether a user is **at risk of heart disease**
- Identifies **possible types of heart disease** based on symptoms
- Generates **graphs and downloadable medical reports**

---

## ✨ Key Features

### 🔍 1. Heart Disease Risk Prediction (ML Model)
- Built and trained a **Machine Learning model** using clinical datasets
- Predicts whether a person **may have heart disease**
- Inputs include:
  - Age
  - Gender
  - Blood Pressure
  - Cholesterol
  - Diabetes status
  - Chest pain & symptoms

---

### 🧠 2. Disease Type Identification (Weighted Symptom System)
- If risk is detected, the system performs **advanced symptom analysis**
- Uses a **JSON-based weighted scoring system**
- Each symptom contributes a weight to multiple heart disease types
- The disease with the **highest total weight** is predicted
- If multiple diseases have equal weight, **all are displayed**

✔️ This logic improves interpretability and accuracy beyond binary prediction

---

### 📊 3. Graphical Health Report
- Automatically generates **visual graphs** for:
  - Risk factors
  - Symptom impact
  - Prediction results
- Graphs are included in the final report for better understanding

---

### 📄 4. Report Generation & Download
- Users can:
  - Generate a detailed **health report**
  - Download the report as a **PDF**
- Report includes:
  - User inputs
  - Prediction result
  - Identified disease(s)
  - Graphical analysis

---

## 🧰 Tech Stack

### 🔹 Backend & ML
- Python
- Flask
- Pandas, NumPy
- Scikit-learn
- Joblib (model serialization)

### 🔹 Frontend
- HTML, CSS
- Bootstrap
- JavaScript (AJAX)

### 🔹 Data & Logic
- JSON (weighted symptom system)
- Machine Learning model for prediction
- Custom rule-based logic for disease classification

---

## 📂 Project Structure

```plaintext
CardioVascular/
│
├── model/                  # Trained ML model files
├── static/
│   ├── css/                # Stylesheets
│   ├── js/                 # Client-side scripts
│   ├── graphs/             # Generated graphs
│   └── video/              # Background/UI video
│
├── templates/              # HTML templates
│   ├── home.html
│   ├── prediction.html
│   ├── report.html
│   ├── report_pdf.html
│   └── error.html
│
├── app.py                  # Flask application entry point
├── heart_disease_info.json # Symptom weightage configuration
├── first.ipynb             # Model training & experimentation
└── heart_disease_report.pdf
```
## ⚙️ How It Works (Flow)
- User enters health details via UI
- ML model predicts risk of heart disease
- If risk detected:
- Symptoms are evaluated using weighted JSON logic
- Disease(s) with highest score are identified
- Graphs are generated
- User can view & download the complete report

## 🧪 Running the Project Locally 
## Clone the repository
```bash
git clone https://github.com/Aiysha-naaz/CardioVascular.git
cd CardioVascular
```
## Install dependencies
```bash
pip install flask pandas joblib scikit-learn
```
## Run the application
```bash
python app.py
```
## Open in browser
```bash
http://127.0.0.1:5000
```

##  Future Enhancements
- Multi-class disease prediction using deep learning
- User authentication & medical history tracking
- Doctor recommendations based on prediction
- Cloud deployment (AWS / Render)
- Improved model accuracy with larger datasets

## 📬 Contact
Aiysha Naaz
GitHub: https://github.com/Aiysha-naaz
