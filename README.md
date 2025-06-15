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


🗃 Datasets
Both datasets are fully synthetic, generated to simulate real-world healthcare scenarios:

🔹 mHealth Behavioral Dataset (synthetic_mhealth_data.csv)
user_id

store

item

page

timestamp

🔹 Patient Clinical Dataset (synthetic_patient_data.csv)
patient_id

age

gender

diagnosis

treatment

comorbidity_score

hospital_visits

treatment_duration_days

outcome (binary)

⚙️ Technologies Used
Python 3.x

Pandas

NumPy

scikit-learn

mlxtend

Faker (for synthetic data generation)

Matplotlib / Seaborn


Setup Instructions
bash
Copy
Edit
# Clone the repository
git clone https://github.com/<your-username>/mHealth-Behavior-and-Outcome-Prediction.git

# Install dependencies
pip install -r requirements.txt

# Run the models
cd behavior_modeling/      # for behavioral prediction
cd outcome_modeling/       # for clinical outcome prediction

📈 Evaluation Metrics
Accuracy

Precision

Recall

F1-Score

Execution Time (for pattern mining)

🔥 Key Algorithms Implemented
Similarity Inference Model (SIM)

Max-Miner Algorithm (Frequent Transaction Mining)

GIT-Tree (Frequent Itemset Mining)

Longest Common Subsequence (LCS)

Logistic Regression

Random Forest Classifier

📌 Citation
If you wish to reference the underlying research ideas, please cite:

User Performance Prediction Based On Their Behavioural Factors
https://link.springer.com/chapter/10.1007/978-981-97-6806-6_1
