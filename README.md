# 🏦 Transaction Risk & Controls — Reporting Automation (Python)

This project automates **transaction risk monitoring and controls reporting** using Python.  
It simulates a real-world **Barclays-style Data Analyst project**, showcasing how to:  

- Ingest and validate financial transaction data  
- Apply **rule-based controls** (high-amount, velocity, blacklist checks)  
- Detect suspicious activity using **anomaly detection (IsolationForest)**  
- Generate automated **reports and visualizations**  

---

## 🚀 Project Highlights
- **Data ingestion & validation**  
  Load transactions from CSV, validate schema, and flag data issues (e.g., negative amounts, missing IDs).  

- **Rule-based controls**  
  - High amount > 10,000 USD  
  - Velocity: > 5 transactions within 30 minutes by same account  
  - Country blacklist (e.g., Russia)  

- **Anomaly detection**  
  Applied `IsolationForest` to identify unusual transactions based on `amount` and `transaction frequency`.  

- **Automated reporting**  
  Generates a timestamped CSV report of exceptions and charts (`matplotlib`) showing:  
  - Transaction amount distribution  
  - Amount vs anomaly score scatter plot  

 
