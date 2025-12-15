# UAV Fault Detection System

A **Machine Learning-powered UAV (drone) fault detection system** using real multivariate drone sensor data (motor RPM, gyroscope, accelerometer). Predicts potential faults in real-time via a FastAPI backend with an interactive HTML/CSS frontend.

---

## Features
- Real-time fault prediction using sensor input
- Backend API using **FastAPI** for ML predictions
- Frontend with **animated drones** and responsive design
- ML model trained using **scikit-learn Random Forest classifier**
- End-to-end **Full-Stack ML project** (Python + FastAPI + HTML/CSS/JS)

---

## Technologies / Skills
- **Machine Learning:** scikit-learn, Anomaly Detection, Sensor Data (IMU, Gyro, Accelerometer, RPM)  
- **Backend:** Python, FastAPI, REST APIs, Model Deployment  
- **Frontend:** HTML, CSS, JavaScript  
- **Tools:** Git, Postman, VS Code  

---
```
##Project Structure

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

##
```
Installation

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

```
cd api
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
---
##
```
Demo / Screenshots

```
This project implements a Machine Learning–based UAV fault detection system using real multivariate drone sensor data. The model is trained to classify fault vs no-fault conditions using motor RPM, gyroscope, and accelerometer readings. 

Below are the demo screenshots showing real-time predictions and backend logs:

FRONTEND:-
![Frontend Prediction]
(https://github.com/payaswinirauta/uav-fault-detection/blob/main/Screenshot%202025-12-15%20194046.png
https://github.com/payaswinirauta/uav-fault-detection/blob/main/Screenshot%202025-12-15%20193821.png
https://github.com/payaswinirauta/uav-fault-detection/blob/main/Screenshot%202025-12-15%20193710.png
https://github.com/payaswinirauta/uav-fault-detection/blob/main/Screenshot%202025-12-15%20193948.png)

BACKEND:-
![Backend Logs]
(https://github.com/payaswinirauta/uav-fault-detection/blob/main/Screenshot%202025-12-15%20193917.png)


_Model training documented in `train_model.ipynb` (Kaggle dataset)_

---
### Results
- Random Forest classifier achieved **94% accuracy** on UAV sensor fault detection.
- Real-time predictions via FastAPI API.
---
---
```
License
MIT License

```
## Developed by
```
Payaswini Rauta










