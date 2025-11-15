# UAV Fault Detection

A machine learning-powered UAV (drone) fault detection system. Predicts potential faults using motor RPM, gyroscope, and accelerometer sensor data. Backend built with FastAPI; frontend uses HTML/CSS with floating drone animations.

---

## Features

- **Real-time fault prediction** via sensor input
- **FastAPI backend** for API-based predictions
- **HTML/CSS frontend** with animated drones
- **Responsive design** for desktop & mobile
- **ML Model:** scikit-learn-based classification

---
```
## Project Structure

uav-fault-detection/
├── frontend/
│ ├── index.html
│ ├── style.css
│ └── assets/images/
│ ├── drone_main.png
│ ├── drone_left.png
│ └── drone_right.png
├── api/
│ └── main.py
├── models/
│ └── uav_fault_model.pkl
├── .gitignore
└── README.md

```

---

## Installation

```bash
git clone https://github.com/payaswinirauta/uav-fault-detection.git
cd uav-fault-detection
python -m venv venv
# Activate virtualenv
# Windows: venv\Scripts\activate
# Mac/Linux: source venv/bin/activate
pip install -r requirements.txt
Usage
Run backend API:

```
##cd api
uvicorn main:app --reload
Open frontend/index.html in a browser.

Enter sensor values and click Predict Fault.

See predicted fault in real-time.

Dependencies
Python 3.11+
FastAPI
scikit-learn==1.2.2
numpy==1.26.4
scipy==1.16.1
Uvicorn
```
```
##License
MIT License
```
```
##Developed by Payaswini Rauta










