# 🧠 Predictive Healthcare: mHealth Behavior & Outcome Prediction

This project implements predictive healthcare analytics inspired by my research work on mobile health (mHealth) behavior mining. It combines advanced sequential pattern mining with supervised machine learning models to predict both **user behavioral patterns** within mobile health applications and **patient clinical outcomes**.

---

## 🔬 Research Motivation

Mobile health (mHealth) platforms generate large-scale interaction data through user activities like browsing, service requests, and health transactions. Predicting user behavior patterns in mHealth is crucial for:

- Personalizing user experiences
- Optimizing service recommendations
- Improving patient care outcomes

This project simulates and models:

- **User behavior prediction** using similarity inference, frequent pattern mining (PMHP-Mine, Max-Miner, GIT-Tree), and Longest Common Subsequence (LCS) algorithms.
- **Clinical outcome prediction** using supervised ML algorithms (Logistic Regression, Random Forest) based on synthetic patient data.

---

## 📊 Problem Statements

### 1️⃣ mHealth User Behavior Prediction

- Mine frequent patterns from app transaction logs
- Discover recurring user behavior sequences
- Predict future user service requests or movement patterns

### 2️⃣ Patient Outcome Prediction

- Predict patient outcomes based on demographics, comorbidities, treatments
- Help healthcare providers optimize treatment plans
- Improve patient care quality

---

## 📁 Project Structure

```bash
User-Behavior-and-Outcome-Prediction/
│
├── data/                    # Synthetic datasets
│   ├── synthetic_mhealth_data.csv
│   └── synthetic_patient_data.csv
│
├── behavior_modeling/       # Sequential behavior mining code (PMHP-Mine, SIM, Max-Miner, GIT-Tree, LCS)
│
├── outcome_modeling/        # ML models for patient outcome prediction
│
├── notebooks/               # Jupyter notebooks for demo and exploration
│
├── utils/                   # Utility functions for data processing
│
├── README.md
└── requirements.txt

