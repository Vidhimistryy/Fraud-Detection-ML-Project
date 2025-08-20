# Fraud-Detection-ML-Project
Fraud Detection &amp; Cybersecurity Monitoring using Machine Learning (XGBoost, Random Forest) and Power BI dashboards for financial transactions.

---

## **Project Overview**
This project detects **fraudulent credit card transactions** using **Machine Learning** and provides actionable insights through **Power BI dashboards**. It combines:

- **Machine Learning:** Random Forest and XGBoost models for fraud prediction  
- **Cybersecurity Monitoring:** Detection of suspicious financial transactions  
- **Data Visualization:** Colab plots and professional Power BI dashboards  

---

## **Dataset**
- **Source:** [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)  
- **Features:** Transaction time, anonymized PCA components (V1–V28), transaction amount, and class label (`0`=normal, `1`=fraud)  

---

## **Tools & Libraries**
- **Python:** pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn, openpyxl  
- **Google Colab:** ML modeling and visualization  
- **Power BI:** Interactive dashboards
- **Optional:** Flask API for real-time predictions  
---

## **Project Workflow**

1. **Data Preprocessing**
   - Handle missing values  
   - Train-test split and standardize features  

2. **Machine Learning**
   - Random Forest & XGBoost models  
   - Handle class imbalance  
   - Evaluate with precision, recall, F1-score, and confusion matrix  

3. **Fraud Alerts**
   - Generate predicted fraud transactions (`fraud_alerts.csv`)  

4. **Visualization**
   - Colab plots: fraud vs normal distribution, fraud amounts, confusion matrix  
   - Power BI dashboard with interactive charts  

5. **Optional**
   - Flask API for real-time prediction  

---

## **Results**
- High-accuracy ML model for fraud detection  
- Actionable fraud alerts in CSV format  
- Professional Power BI dashboards for reporting  

---

## **Project Overview**
This project detects **fraudulent credit card transactions** using **Machine Learning** and provides actionable insights through **Power BI dashboards**. It combines:

- **Machine Learning:** Random Forest and XGBoost models for fraud prediction  
- **Cybersecurity Monitoring:** Detection of suspicious financial transactions  
- **Data Visualization:** Colab plots and professional Power BI dashboards  

---

## **Dataset**
- **Source:** [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)  
- **Features:** Transaction time, anonymized PCA components (V1–V28), transaction amount, and class label (`0`=normal, `1`=fraud)  

---

## **Tools & Libraries**
- **Python:** pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn, openpyxl  
- **Google Colab:** ML modeling and visualization  
- **Power BI:** Interactive dashboards  
- **Optional:** Flask API for real-time predictions  

---

## **Project Workflow**

1. **Data Preprocessing**
   - Handle missing values  
   - Train-test split and standardize features  

2. **Machine Learning**
   - Random Forest & XGBoost models  
   - Handle class imbalance  
   - Evaluate with precision, recall, F1-score, and confusion matrix  

3. **Fraud Alerts**
   - Generate predicted fraud transactions (`fraud_alerts.csv`)  

4. **Visualization**
   - Colab plots: fraud vs normal distribution, fraud amounts, confusion matrix  
   - Power BI dashboard with interactive charts  

5. **Optional**
   - Flask API for real-time prediction  

---

## **Results**
- High-accuracy ML model for fraud detection  
- Actionable fraud alerts in CSV format  
- Professional Power BI dashboards for reporting  

---

## **How to Run**
1. Open `Fraud_Detection_Colab.ipynb` in Google Colab  
2. Install required libraries:
```bash
!pip install -r requirements.txt

---

## Repository Structure
Fraud-Detection-ML-Project/
├─ Fraud_Detection_Colab.ipynb       # Main notebook
├─ fraud_alerts.csv                  # Predicted fraud transactions
├─ requirements.txt                  # Python environment
├─ PowerBI_Screenshots/              # Dashboard screenshots
├─ model/                             # Saved ML model (optional)
│   └─ fraud_model.pkl
└─ README.md                         # Project description

---
