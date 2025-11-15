# UAV Fault Detection System

A machine learning-powered UAV (drone) fault detection system. This project predicts potential drone faults using sensor data (motor RPM, gyroscope, and accelerometer readings). It includes a FastAPI backend for API-based predictions and a responsive HTML/CSS frontend with floating drone animations.

---

## Features

- **Real-time fault prediction:** Input sensor data to predict faults instantly.
- **Frontend:** Clean HTML/CSS interface with floating drone animations.
- **Backend:** FastAPI-based REST API for ML model predictions.
- **Machine Learning:** Uses a trained scikit-learn model (`uav_fault_model.pkl`) for classification.
- **Responsive design:** Works on desktop and mobile screens.

---

## Project Structure

uav-fault-detection/
│
├── frontend/
│ ├── index.html
│ ├── style.css
│ └── assets/
│ └── images/
│ ├── drone_main.png
│ ├── drone_left.png
│ └── drone_right.png
│
├── api/
│ └── main.py
│
├── models/
│ └── uav_fault_model.pkl
│
├── .gitignore
└── README.md

yaml
Copy code

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/payaswinirauta/uav-fault-detection.git
cd uav-fault-detection
Create a virtual environment and activate it:

bash
Copy code
python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
Start the backend API:

bash
Copy code
cd api
uvicorn main:app --reload
Open frontend/index.html in your browser.

Enter drone sensor values (motor RPM, gyro, and accelerometer readings) and click Predict Fault.

View the predicted fault in real-time.

Dependencies
Python 3.11+

FastAPI

scikit-learn==1.2.2

numpy==1.26.4

scipy==1.16.1

Uvicorn

Screenshots
Add screenshots of your frontend UI and drone animation here

License
This project is licensed under the MIT License.

UAV Fault Detection System by Payaswini Rauta

vbnet
Copy code

Ye **README** professional aur clean hai, aur GitHub par direct paste karne se sab structure aur usage clearly dikh jaayega.  

Agar chaho to main **`requirements.txt`** bhi abhi ready kar doon, taaki aap GitHub me directly upload kar sako. Chahoge?






