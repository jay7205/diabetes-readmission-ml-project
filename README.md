# diabetes-readmission-ml
“ML project for predicting 30-day hospital readmission using the Diabetes 130-US Hospitals dataset.”

2. Problem Statement
Write what the dataset is and what you are predicting:

Predict whether a diabetic patient will be readmitted within 30 days.

Healthcare domain: high sensitivity required.

Dataset: Diabetes 130-US Hospitals dataset (1999–2008).

4. Dataset Description

Include:
100k+ records
50+ features


Highly imbalanced
Binary target:
<30 → 1
>30 / NO → 0


project/
│── data/
│── notebooks/
│── models/
│── results/
│── README.md
│── requirements.txt

Methodology Sections

EDA

Preprocessing

Feature Engineering

Train/Val/Test Split

Baseline Models

Class Imbalance Handling

Advanced Models

Evaluation Metrics

<img width="800" height="267" alt="MODEL_COMP WITH ALL EVAL METRICS" src="https://github.com/user-attachments/assets/199f9327-98f5-4f4a-839b-2935d5793b94" />
<img width="846" height="628" alt="ROC_CURVE_V4" src="https://github.com/user-attachments/assets/eb6c2c21-e2e8-4d93-966d-d2982a53274e" />
<img width="536" height="391" alt="BEST_ROC_WITH SMOTE,SAMPLING" src="https://github.com/user-attachments/assets/25f9e751-ebdb-49cf-8765-9be314355644" />

Limitations:

Dataset imbalanced

No time-series modeling

Readmission reason unknown

Missing external clinical validation

Lower accuracy acceptable due to class imbalance

Future Work

Collect more features (bloodwork, vitals)

Use deep learning models

Use sequential (LSTM) modeling for patient history

Better hyperparameter tuning (Optuna)

Deploy API using FastAPI

dependencies:
pip install -r requirements.txt




