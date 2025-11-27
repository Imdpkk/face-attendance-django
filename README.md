<h1 align="center">Face Recognition Attendance System (Django)</h1>

<p align="center">
  <img src="https://img.shields.io/badge/python-3.10-blue.svg" />
  <img src="https://img.shields.io/badge/django-5.2-green.svg" />
  <img src="https://img.shields.io/badge/opencv-4.x-red.svg" />
  <img src="https://img.shields.io/badge/facenet--pytorch-2.6-yellow.svg" />
  <img src="https://img.shields.io/badge/license-MIT-lightgrey.svg" />
</p>


## 🎯 Overview

This is a **real-time Face Recognition Attendance System** built using **Django**, **OpenCV**, and **FaceNet (MTCNN + InceptionResnetV1)**.

It captures live video, detects faces, compares embeddings, and automatically logs **Check-In / Check-Out** attendance.  
This project is suitable for:

- Colleges & Universities  
- Offices & Companies  
- Security Access Systems  
- Labs & Research Centres  

---

## 🚀 Features

### 🧠 Face Recognition
- MTCNN for face detection  
- FaceNet for generating embeddings  
- Works with webcam or IP camera  

### 📸 Student Image Capture
- Capture multiple face images  
- Clean folder management  
- Automatic face encoding  

### 📊 Attendance Automation
- Auto Check-In / Check-Out  
- Stores history in SQLite  
- User-friendly admin dashboard  

### 🔊 Sound Notifications
- Plays a success sound using **pygame**  

### 🔐 Admin Controls
- Add/delete students  
- Approve or authorize users  
- View detailed attendance  

---

## 🛠 Tech Stack

| Technology | Purpose |
|-----------|----------|
| **Python 3.10** | Backend logic |
| **Django 5.x** | Web framework |
| **OpenCV** | Camera & face capture |
| **Facenet-Pytorch** | Face embeddings |
| **SQLite** | Default database |
| **Pygame** | Sound alerts |

---

## 📥 Installation Guide

### 1️⃣ Clone the Project
```bash
git clone https://github.com/Imdpkk/face-attendance-django.git
cd face-attendance-django
2️⃣ Create & Activate Virtual Environment
bash
Copy code
python -m venv venv
venv\Scripts\activate
3️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt
4️⃣ Apply Migrations
bash
Copy code
python manage.py migrate
5️⃣ Start Server
bash
Copy code
python manage.py runserver
6️⃣ Open in Browser
👉 http://127.0.0.1:8000/

☁️ Cloud & DevOps Improvements (Future Scope)
These will make your project Cloud-ready and perfect for your AWS & DevOps resume.

🟦 1. AWS S3
Store student images + embeddings securely.

🟩 2. AWS EC2
Host the Django project.

🟨 3. AWS RDS
Move database from SQLite → PostgreSQL.

🟥 4. AWS Lambda
Automate embedding generation.

🔵 5. GitHub Actions (CI/CD)
Auto deploy to EC2 on push.

🟪 6. Docker Support
Containerize the entire application.

🔮 Future Enhancements
Mask detection

QR + Face hybrid attendance

Mobile App API

Admin analytics dashboard

OTP/Email alerts

Nginx + Gunicorn deployment

🧑‍💻 Author
Deepak Vishwakarma

GitHub: https://github.com/Imdpkk

LinkedIn: https://www.linkedin.com/in/deepak-vishwakarma-846ba1269/

Email: deepvishwakarma.2114@gmail.com
