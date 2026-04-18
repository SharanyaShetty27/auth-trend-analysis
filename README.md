# 🔐 Failed Authentication Trend Analysis  

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Domain-Cybersecurity-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/ML-Linear%20Regression-yellow?style=for-the-badge">
</p>

---

## 📌 Overview  
A **Python-based cybersecurity analysis system** that monitors failed authentication attempts over time to detect anomalies, identify attack campaigns, and predict future threats.

This project simulates real-world **Security Operations Center (SOC)** behavior by applying time-series analysis and machine learning techniques to authentication logs.

---

## 🚀 Features  

✨ **Core Functionalities**
- 📊 Time-series analysis of failed logins  
- ⚠️ Dynamic anomaly detection (rolling mean + std)  
- 🔍 Attack campaign detection (multi-point anomalies)  
- 🤖 Future trend prediction using Linear Regression  
- 🌐 Suspicious IP identification  

📈 **Visualization**
- Trend analysis graph  
- Anomaly highlighting  
- Attack campaign markers  
- Prediction curve  
- Top attacking IP bar chart  

---
## 📊 Output
- Failed authentication trend graph  
- Anomaly detection visualization  
- Attack campaign indicators  
- Predicted future trend  
- Top suspicious IP bar chart  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 📂 Project Structure

auth-trend-analysis/
│
├── auth_trend_analysis.ipynb
├── real_auth_logs.csv
├── outputs/
├── README.md
└── requirements.txt


---

## ▶️ How to Run

### Step 1: Clone Repository

git clone https://github.com/SharanyaShetty27/auth-trend-analysis.git

cd auth-trend-analysis


### Step 2: Install Dependencies

pip install -r requirements.txt


### Step 3: Run Notebook
Open:

auth_trend_analysis.ipynb

Run all cells (Kernel → Run All)

---

## 📈 Sample Metrics
- Total Failed Attempts  
- Total Anomalies Detected  
- Attack Campaign Points  

---

## 🎯 Use Cases
- Cybersecurity monitoring  
- Intrusion detection systems  
- SOC (Security Operations Center) analysis  
- Log-based threat detection  
- Academic projects  

---

## ⚠️ Limitations
- Uses simulated dataset  
- Basic prediction model  
- No real-time processing  

---

## 🚀 Future Enhancements
- Real-time monitoring  
- Machine learning-based detection  
- Dashboard (Streamlit)  
- Geo-location analysis  

---

## 👩‍💻 Author
Sharanya P Shetty  
MTech Cybersecurity | B.E AI&ML 

---

## 💬 Project Description
A Python-based system that analyzes failed authentication trends using time-series techniques to detect anomali
## 🧠 System Workflow  

```mermaid
flowchart LR
A[Authentication Logs] --> B[Preprocessing]
B --> C[Failed Login Filtering]
C --> D[Time-Series Aggregation]
D --> E[Threshold Calculation]
E --> F[Anomaly Detection]
F --> G[Attack Campaign Detection]
G --> H[Prediction Model]
H --> I[Visualization & Insights]

