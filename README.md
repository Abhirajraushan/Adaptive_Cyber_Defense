# Adaptive Cyber Defense Using Generative AI for Real-Time Threat Detection and Adaptive Authentication

<style>
/* Inline CSS for GitHub's markdown preview limitations */
h1, h2, h3 {
    color: #2e86de;
    font-family: Arial, sans-serif;
    font-weight: bold;
    border-bottom: 2px solid #2e86de;
    padding-bottom: 5px;
}

h2 {
    color: #27ae60;
    font-size: 24px;
    padding-top: 10px;
}

code, pre {
    background-color: #f5f5f5;
    padding: 5px;
    border-radius: 4px;
}

li {
    line-height: 1.6;
    margin: 5px 0;
}

table {
    width: 100%;
    border-collapse: collapse;
}

th, td {
    padding: 8px;
    border: 1px solid #ddd;
    text-align: left;
}

blockquote {
    background: #f9f9f9;
    border-left: 4px solid #ccc;
    padding: 10px;
    font-style: italic;
    color: #555;
}
</style>

## 📘 Introduction and Objective
*Title:* Adaptive Cyber Defense Using Generative AI for Real-Time Threat Detection and Adaptive Authentication

*Objective:* 
The goal of this project is to develop a cybersecurity system leveraging Generative AI for real-time threat detection and adaptive user verification.

---

## 📂 Project Structure
The project is organized as follows:

```bash
├── network_activity.csv              # Dataset file
├── anomaly_detection.py              # Anomaly detection module using LSTM
├── phishing_detection.py             # Phishing and malware detection using RandomForest
├── adaptive_authentication.py        # User behavior-based adaptive authentication
├── app.py                            # Flask app for dashboard
├── models.py                         # Database models
├── insert.py                         # Script for data insertion
├── create_table.py                   # Script for creating database tables
├── check_table.py                    # Script to check data in tables
└── templates/
    └── dashboard.html                # HTML template for threat dashboard
