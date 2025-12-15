# UAV Fault Detection

This project implements a Machine Learning–based UAV fault detection system using
real multivariate drone sensor data. The model is trained to classify fault vs no-fault
conditions using motor RPM, gyroscope, and accelerometer readings.

Model training is documented in `train_model.ipynb` (trained on Kaggle dataset).

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
---
## Demo / Screenshots

```
This project implements a Machine Learning–based UAV fault detection system using real multivariate drone sensor data. The model is trained to classify fault vs no-fault conditions using motor RPM, gyroscope, and accelerometer readings. 

Below are the demo screenshots showing real-time predictions and backend logs:

FRONTEND:-
https://github.com/payaswinirauta/uav-fault-detection/blob/main/Screenshot%202025-12-15%20194046.png
https://github.com/payaswinirauta/uav-fault-detection/blob/main/Screenshot%202025-12-15%20193821.png
https://github.com/payaswinirauta/uav-fault-detection/blob/main/Screenshot%202025-12-15%20193710.png
https://github.com/payaswinirauta/uav-fault-detection/blob/main/Screenshot%202025-12-15%20193948.png

BACKEND:-
https://github.com/payaswinirauta/uav-fault-detection/blob/main/Screenshot%202025-12-15%20193917.png


_Model training documented in `train_model.ipynb` (Kaggle dataset)_

---
```
License
MIT License
---
```
Developed by Payaswini Rauta










