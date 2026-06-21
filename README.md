# ⚡ Electricity Theft Detection System

## 📌 Overview

The Electricity Theft Detection System is a Machine Learning-based web application developed using Python and Streamlit. It analyzes electricity consumption patterns and identifies potential electricity theft cases using a Random Forest Classifier.

This project provides district-wise, town-wise, and area-wise fraud detection along with model performance analysis and consumer-level prediction.

---

## ✨ Features

- 🔐 Secure Login System
- 📊 Model Performance Dashboard
- 🏙 District-wise Fraud Detection
- 🏘 Town-wise Fraud Detection
- 📍 Area-wise Fraud Detection
- 👤 Fraud Consumer Details
- 🤖 Machine Learning Prediction
- 📥 Download Fraud Consumer List (CSV)

---

## 🛠 Technologies Used

- Python
- Streamlit
- Pandas
- Scikit-learn
- Random Forest Classifier
- Joblib

---

## 📂 Project Structure

```
Electricity-Theft-Detection/
│
├── app.py
├── train_model.py
├── requirements.txt
├── README.md
├── dataset/
│   └── electricity_data.csv
└── model/
    ├── model.pkl
    ├── scaler.pkl
    └── metrics.pkl
```

---

## ⚙ Machine Learning Workflow

1. Load electricity consumption dataset
2. Preprocess categorical values
3. Split data into training and testing sets
4. Apply StandardScaler
5. Train Random Forest Classifier
6. Evaluate model performance
7. Save trained model and scaler
8. Predict electricity theft using the Streamlit application

---

## 📈 Model Performance

| Metric | Score |
|---------|---------|
| Accuracy | 100% |
| Precision | 100% |
| Recall | 100% |
| F1 Score | 100% |

> **Note:** This project uses a synthetic dataset created for educational and demonstration purposes.

---

## 🚀 How to Run

### Install dependencies

```
pip install -r requirements.txt
```

### Train the model

```
python train_model.py
```

### Run the Streamlit application

```
streamlit run app.py
```

---

## 📷 Screenshots

### Login Page

(Add login_page.png)

### Model Analysis

(Add model_analysis.png)

### District Detection

(Add district_detection.png)

### Fraud Consumer Details

(Add fraud_details.png)

---

## 🎯 Future Improvements

- Real-time smart meter integration
- Deep Learning based detection
- Interactive Power BI dashboard
- Email/SMS alert system
- Cloud deployment

---

## 👩‍💻 Author

**R. Devadharshini**

B.Tech Artificial Intelligence and Data Science

Kingston Engineering College
