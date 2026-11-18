# Network Intrusion Detection System using Machine Learning

## Overview

This project is a Machine Learning–based Network Intrusion Detection System (IDS) developed using Python and Flask.  
It predicts whether incoming network traffic is **Normal** or an **Attack**, and if malicious, it also identifies the **attack type**.

The system uses trained ML models and provides a web interface for real-time prediction.

---

## Features

- Web-based interface using Flask  
- Binary classification (Normal vs Attack)  
- Attack type prediction  
- Feature scaling using StandardScaler  
- Pre-trained ML models using Joblib  
- Real-time prediction  
- Simple user interface  

---

## Tech Stack

- Python  
- Flask  
- NumPy  
- Pandas  
- Scikit-learn  
- Joblib  
- HTML (Flask Templates)  
- Git & GitHub  

---

## Project Structure

```bash
project-folder/
│
├── app.py
├── binary_ids_model.joblib
├── attack_type_model.joblib
├── scaler.joblib
├── templates/
│ └── index.html
├── screenshots/
│ ├── ids.png
│ └── ids1.png
├── README.md
└── venv/
```

---

## Dataset

The models were trained using a dataset inspired by **NSL-KDD / KDD Cup 99**, containing network traffic features such as:

- duration  
- src_bytes  
- dst_bytes  
- count  
- srv_count  
- serror_rate  
- same_srv_rate  
- diff_srv_rate  
- dst_host_count  
- dst_host_srv_count  

---

## Model Performance

- Binary Classification Accuracy: ~95%  
- Attack Type Classification Accuracy: ~90%  

*(Accuracy may vary depending on preprocessing and dataset.)*

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Prem20-creator/IDS.git
cd project-folder
```
### 2️⃣ Create Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate
```
### 3️⃣ Install Dependencies
```bash
pip install flask numpy pandas scikit-learn joblib
```
### 4️⃣ Run Application
```bash
python app.py
```
### Open browser:
```bash
http://127.0.0.1:5000/
```

### How to Use

-  Enter network traffic feature values
- Click Predict
- View results:
  - Normal / Attack
  - Attack Type
    
### Future Enhancements
- Upload CSV dataset
- Improve UI
- Authentication
- Cloud deployment
- Dashboard visualization
- Real-time packet capture
---
### Learning Outcomes
- Machine Learning in Cybersecurity
- Flask application development
- ML model deployment
- Feature scaling
- End-to-end ML workflow
---
