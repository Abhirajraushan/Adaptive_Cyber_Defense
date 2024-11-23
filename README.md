# Adaptive Cyber Defense Using Generative AI for Real-Time Threat Detection and Adaptive Authentication

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


#🛠️ Setup Steps
Follow these steps to set up and run the project:

Step 1: Install Packages
Install the required packages:
pip install pandas scikit-learn tensorflow flask flask_s

Step 2: Create Database Tables
Run the following script to create the necessary database tables:
python create_table.py

Step 3: Run the Application
Start the application:
python app.py

## 4. Modules Description
Each module in the project has a specific function:
Anomaly Detection: Uses an LSTM neural network to detect unusual network activity.
Phishing Detection: Uses Random Forest to classify potential phishing or malware threats.
Adaptive Authentication: Verifies users based on typing speed or other behavioral patterns.
Dashboard: Displays real-time threat intelligence data for security teams to respond promptly.


##5. Flowcharts
Flowcharts explaining the project flow are available to give a clear overview of the workflow:

Overall Project Workflow
Threat Intelligence Dashboard-Wireframe
Anomaly Detection Process
Phishing Detection Process
Adaptive Authentication Process



##6. Code Comments and Clean Structure
Each script contains minimal and concise comments for easy understanding. Code indentation and naming conventions are consistent throughout the project.


