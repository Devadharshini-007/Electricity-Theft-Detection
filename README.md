# ⚡ Electricity Theft Detection System

A Machine Learning-based web application that detects electricity theft using consumer electricity consumption patterns. The system provides district-wise, town-wise, and area-wise fraud detection with an interactive Streamlit dashboard.

---

## 📌 Overview

This project uses a Random Forest Machine Learning model to identify suspicious electricity consumption and predict possible electricity theft.

The application allows electricity board officers to:

- Secure login
- View model performance
- Detect fraud district-wise
- Detect fraud town-wise
- Detect fraud area-wise
- View fraud consumer details
- Download fraud consumer list
- Predict whether a consumer is normal or involved in electricity theft

---

## 🚀 Features

- 🔐 Login Authentication
- 📊 Model Performance Analysis
- 🏙 District-wise Fraud Detection
- 🌍 Town-wise Fraud Detection
- 📍 Area-wise Fraud Detection
- 🚨 Fraud Consumer List
- 👤 Consumer Detail Analysis
- 🤖 Machine Learning Prediction
- 📥 Download Fraud Report (CSV)

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
├── README.md
├── requirements.txt
│
├── dataset/
│   └── electricity_data.csv
│
├── images/
│   ├── login_page.jpeg
│   ├── model_analysis.jpeg
│   ├── district_detection.jpeg
│   └── fraud_detection.jpeg
│
└── model/
    ├── model.pkl
    ├── scaler.pkl
    └── metrics.pkl
```

---

## 📊 Machine Learning Model

Algorithm Used:

**Random Forest Classifier**

Features:

- Monthly Consumption
- Average 6 Months Consumption
- Area Average
- Feeder Average
- Deviation
- Sudden Drop
- Area Mismatch
- Feeder Mismatch

Target:

- NTL_Label (Normal / Theft)

---

## 📷 Screenshots

### 🔐 Login Page

![Login Page](images/login_page.jpeg)

---

### 📊 Model Performance

![Model Analysis](images/model_analysis.jpeg)

---

### 🔎 District Detection

![District Detection](images/district_detection.jpeg)

---

### 🚨 Fraud Detection

![Fraud Detection](images/fraud_detection.jpeg)

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/Devadharshini-007/Electricity-Theft-Detection.git
```

Go to the project folder

```bash
cd Electricity-Theft-Detection
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the model

```bash
python train_model.py
```

Run the Streamlit application

```bash
streamlit run app.py
```

---

## 🔑 Login Credentials

### Admin

Username

```
admin
```

Password

```
1234
```

### Officer

Username

```
officer
```

Password

```
1234
```

---

## 📈 Model Performance

| Metric | Score |
|----------------|---------|
| Accuracy | 1.00 |
| Precision | 1.00 |
| Recall | 1.00 |
| F1 Score | 1.00 |

---

## 🎯 Future Improvements

- Real-time smart meter integration
- Deep Learning models
- GIS Map Visualization
- Email and SMS Alerts
- Cloud Deployment
- Mobile Application

---

## 👩‍💻 Author

**R. Devadharshini**

B.Tech Artificial Intelligence and Data Science

GitHub:

https://github.com/Devadharshini-007

LinkedIn:

www.linkedin.com/in/deva-dharshini-12b7b1325

---

## ⭐ If you like this project

Give this repository a ⭐ Star on GitHub.
