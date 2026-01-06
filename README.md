Employee Expense Anomaly Detection Engine

This project implements an unsupervised anomaly detection system
to identify suspicious employee expense claims.


Key Features:

-> Unsupervised learning (Isolation Forest)
-> Detects inflated claims & fake reimbursements
-> Batch anomaly detection
-> Real-time anomaly simulation
-> Concept drift detection using ADWIN


Tech Stack:

-> Python
-> Pandas
-> Scikit-learn
-> River
-> Jupyter Notebook


Project Flow:

1. Load raw expense data
2. Preprocess & scale features
3. Train anomaly detection model
4. Detect anomalies (batch)
5. Monitor concept drift
6. Simulate real-time detection