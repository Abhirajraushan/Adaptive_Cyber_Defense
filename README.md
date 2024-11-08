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
![WhatsApp Image 2024-11-06 at 19 56 57_482ae71c](https://github.com/user-attachments/assets/18bba497-d5fa-4d45-a061-cf0bb7fc1b95)

Threat Intelligence Dashboard-Wireframe
![WhatsApp Image 2024-11-06 at 19 53 32_8539b231](https://github.com/user-attachments/assets/9ea0996d-bed0-4aeb-90bb-4dda23277169)

Anomaly Detection Process
![ANOMALY](https://github.com/user-attachments/assets/8b3339b3-a4b8-4e18-a5e0-0c6e47499679)

Phishing Detection Process
![Phising](https://github.com/user-attachments/assets/d4811547-b45e-46f9-bfa1-1a1302cb2020)

Adaptive Authentication Process
![ADAPTIVE](https://github.com/user-attachments/assets/4f787a09-5bdb-48b1-92b2-c72c17ce4b95)


##6. Code Comments and Clean Structure
Each script contains minimal and concise comments for easy understanding. Code indentation and naming conventions are consistent throughout the project.

