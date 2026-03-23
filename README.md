# 🗑️ Garbage Detection and Reporting System

The **Garbage Detection and Reporting System** is an application that automatically detects garbage in images/videos using **Computer Vision (OpenCV)** and generates reports through a **Flask web interface**. This project helps improve cleanliness monitoring by providing an automated way to identify garbage and notify authorities for timely action.

---

## 🚀 Features

- 📸 Detect garbage in images and videos using trained models.  
- 🌐 Flask web interface for uploading media and viewing results.  
- 📊 Report generation with detection details.  
- 🔔 Option to notify authorities about garbage presence.  
- 📂 Storage of uploaded images and generated reports.  
- ⚡ Real-time detection from live camera feed (optional).  

---

## 🏗️ Project Architecture

Garbage Detection & Reporting System
│
├── Image/Video Input (Camera, Upload, Dataset)
│
├── Preprocessing (Resizing, Normalization)
│
├── Detection Model (OpenCV + ML/Deep Learning)
│
├── Flask Web App (Frontend + Backend)
│
├── Report Generation (Detected Garbage, Timestamp, Location)
│
└── Database


---

## 📂 Folder Structure
📦 Garbage-Detection-Reporting
│
├── app.py # Flask application entry point
├── requirements.txt # Dependencies
├── static/ # Static files (CSS, JS, images)
├── templates/ # HTML templates for Flask
├── reports/ # Generated reports
└── README.md # Project documentation


---

## ⚙️ Installation & Setup

1️⃣ Clone the Repository
```bash
git clone https://github.com/Udayraj-Mathane/AI-Powered-Garbage-Detection.git
cd garbage-detection-reporting


2️⃣ Create Virtual Environment
python -m venv venv
source venv/bin/activate      # On Mac/Linux
venv\Scripts\activate         # On Windows

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Application
python app.py


🧑‍💻 Technologies Used

Python

OpenCV – Image Processing & Object Detection

Flask – Web Framework

NumPy, Pandas – Data Handling

Matplotlib/Seaborn– Visualization (Reports)

YOLO / CNN (Optional)/Roboflow  – Deep Learning Garbage Detection


📊 Example Workflow

Upload an image/video via Flask web app.

System detects garbage using the trained ML model.

Annotated image with bounding boxes is displayed.

Report is generated with:

Image preview

Garbage detection confidence

Timestamp & Location


✅ Future Enhancements

📍 GPS-based location tagging.

📱 Mobile app integration.

☁️ Cloud deployment (AWS, Azure, GCP).

🧠 Higher accuracy with YOLOv8 or custom-trained CNN.

Status update



