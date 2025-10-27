🚗 Smart Anti-Sleep Alert System for Drivers Using Eye Blink Detection
👁️ Project Overview

This project is designed to detect driver drowsiness using eye blink detection.
It continuously monitors the driver's eyes through a webcam and triggers an alert sound if the driver’s eyes remain closed for more than 2 seconds.
The main goal is to prevent road accidents caused by fatigue and loss of alertness among drivers.
🧠 Features

Real-time eye and face detection using OpenCV

Beep alert sound when drowsiness is detected

Works on Windows, Linux, and MacOS

Simple and lightweight design

Promotes road safety through AI-based monitoring

🧰 Technologies Used

Python 3.x

OpenCV (Computer Vision Library)

Haar Cascade Classifiers

Time, OS, and Platform libraries
⚙️ Installation & Execution Steps
🔹 Step 1: Clone the Repository
git clone https://github.com/your-username/mini-project.git
🔹 Step 2: Navigate to the Project Folder
cd mini-project

🔹 Step 3: Install Required Packages

Make sure Python is installed on your system, then run:

pip install opencv-python


(Optional – for sound on Linux/Mac)

sudo apt install paplay

🔹 Step 4: Run the Project
python smart_anti_sleep_alert.py

🔹 Step 5: How It Works

The webcam starts detecting your face and eyes in real time.

If eyes remain closed for more than 2 seconds, a beep sound is triggered.

The window will show messages like “AWAKE”, “Eyes Closed”, or “WAKE UP!”.

Press ‘q’ to quit the program.

📂 Project Structure
mini-project/
│
├── smart_anti_sleep_alert.py     # Main source code file  
├── README.md                     # Project description and setup guide  
└── requirements.txt              # (Optional) Python dependencies list  

📸 Output Messages

🟢 AWAKE – Eyes open, normal state

🟡 Eyes Closed – Temporary blink detected

🔴 DROWSY / WAKE UP! – Eyes closed too long, alarm triggered

🚀 Future Enhancements

Integration with Raspberry Pi for real-time vehicle use

Addition of cloud or GPS alerts for emergency notifications

Implementation of deep learning for better accuracy

👨‍💻 Developed By

Lingesh B, Veera, Akshay, Ravee V
Panimalar Engineering College
Department of Computer Science and Engineering
Academic Year: 2025
