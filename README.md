# DATA RISK ANALYZER

**Data Risk Analyzer** is a **web-based application** that allows users to assess and visualize system security risks. Users can input critical security parameters such as password strength, two-factor authentication, open ports, software updates, and data encryption to calculate a risk score and get actionable recommendations.

---

## Features

- User registration and login system
- **Risk assessment form** for quick evaluation
- Risk levels: **LOW, MEDIUM, HIGH** with recommendations
- History table to track past risk records
- Option to delete individual or all records
- **Responsive and modern design** using Bootstrap and Chart.js

---

## Technologies

- **Backend:** Python, Flask  
- **Database:** SQLite, SQLAlchemy  
- **Frontend:** HTML, CSS, Bootstrap 5, Chart.js  
- **Password security:** Werkzeug

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/zeynepmanap/data-risk-analyzer.git
cd data-risk-analyzer

2.Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # Linux / Mac
venv\Scripts\activate     # Windows

3.Install dependencies:
pip install -r requirements.txt

4.Run the application:
python app.py

5.Open the app in your browser:
http://127.0.0.1:5000/

Usage
Register a new account or log in with an existing one
Fill out the Risk Assessment form on the dashboard
View the risk score, level, and recommendation
Track historical records in the table and delete if necessary
Observe the risk trend in the chart

Project Structure

data-risk-analyzer/
│
├─ app.py               # Flask application
├─ models.py            # Database models
├─ risk_engine.py       # Risk calculation logic
├─ requirements.txt     # Python dependencies
├─ templates/           # HTML templates
│   ├─ base.html
│   ├─ dashboard.html
│   ├─ login.html
│   └─ register.html
└─ static/              # CSS, JS, and other assets

Development Notes
Risk score is calculated using password strength, two-factor authentication, open ports, software updates, and encryption
Average score and trend are calculated from historical records
Chart.js is used for visualizing the risk trend

License
This project is licensed under the MIT License.
