# 🎓 AI-Powered Student Engagement System

<p align="center">

<img src="https://github.com/user-attachments/assets/4ff8e135-a2c3-4572-a1eb-59f9b4370eeb" width="900"/>

</p>

<p align="center">
An AI-powered computer vision system that analyzes classroom videos and evaluates student engagement using Deep Learning and Computer Vision.
</p>

<p align="center">

<a href="https://student-engagement-ai.streamlit.app/">
<img src="https://img.shields.io/badge/🚀%20Live%20Demo-Open%20Website-success?style=for-the-badge"/>
</a>

<a href="https://hub.docker.com/r/vahith05/student-engagement-system">
<img src="https://img.shields.io/badge/🐳%20Docker%20Hub-Image-blue?style=for-the-badge&logo=docker"/>
</a>

<a href="https://github.com/YOUR_USERNAME/student_engagement_system">
<img src="https://img.shields.io/badge/💻%20GitHub-Source%20Code-black?style=for-the-badge&logo=github"/>
</a>

</p>

---

# 📖 Overview

The **AI-Powered Student Engagement System** is a computer vision-based application designed to analyze classroom videos and measure student engagement using artificial intelligence.

The system uses **YOLO object detection**, **TensorFlow-based deep learning models**, and **OpenCV video processing** to detect students, analyze classroom activities, and generate meaningful engagement insights through an interactive Streamlit dashboard.

This project aims to assist educators by providing automated analysis of classroom environments and helping understand student participation levels.

---

# ✨ Features

## 🎥 Video Analysis
- Upload classroom videos
- Extract and process video frames
- Automated AI-based analysis

## 🤖 Computer Vision
- Student detection using YOLO
- Object tracking
- Frame-level analysis

## 📊 Analytics Dashboard
- Engagement statistics
- Visual reports
- Processed video outputs
- Interactive data visualization

## 🚀 Deployment
- Streamlit web application
- Docker container support
- Ready-to-deploy architecture

---

# 📸 Application Screenshots

## 🏠 Home Page

<img src="https://github.com/user-attachments/assets/4ff8e135-a2c3-4572-a1eb-59f9b4370eeb" width="900"/>

---

## 📤 Video Upload

<img src="https://github.com/user-attachments/assets/b00623b8-4a1e-464a-8013-e35c6458caec" width="900"/>

---

## 📊 Analytics Dashboard

<img src="https://github.com/user-attachments/assets/b21cbb99-12f8-4cba-94f5-f0b5f1fa2db2" width="900"/>

<img src="https://github.com/user-attachments/assets/8237207f-436e-46d4-9e43-45bacac1d83d" width="900"/>

---

## 🎬 Processed Output

<img src="https://github.com/user-attachments/assets/ad588feb-a7bf-4dc8-9773-17f0f1cf27fd" width="900"/>

---

# 🏗️ System Architecture

```text
                 Classroom Video
                        |
                        ▼
              Streamlit Web Interface
                        |
                        ▼
              Video Frame Extraction
                        |
                        ▼
              YOLO Object Detection
                        |
                        ▼
          Engagement Feature Processing
                        |
                        ▼
              AI Engagement Analysis
                        |
                        ▼
             Analytics Visualization
                        |
                        ▼
                  Final Report
```

---

# 🛠️ Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python 3.10 |
| Web Framework | Streamlit |
| Deep Learning | TensorFlow |
| Object Detection | YOLO (Ultralytics) |
| Computer Vision | OpenCV |
| Data Processing | NumPy, Pandas |
| Visualization | Matplotlib |
| Containerization | Docker |

---

# 📂 Project Structure

```text
student_engagement_system/
│
├── analytics/          # Analytics generation
├── config/             # Configuration files
├── models/             # AI models
├── outputs/            # Generated outputs
├── processing/         # Video processing pipeline
├── tracking/           # Object tracking logic
├── utils/              # Helper functions
│
├── app.py              # Streamlit application
├── requirements.txt    # Python dependencies
├── Dockerfile          # Docker configuration
├── docker-compose.yaml
├── .dockerignore
├── .gitignore
└── README.md
```

---

# 🚀 Quick Start

## Option 1: Run Locally

### Clone repository

```bash
git clone https://github.com/YOUR_USERNAME/student_engagement_system.git

cd student_engagement_system
```

### Create virtual environment

```bash
python -m venv .venv
```

### Activate environment

Windows:

```bash
.venv\Scripts\activate
```

Linux/macOS:

```bash
source .venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Start application

```bash
streamlit run app.py
```

Application URL:

```
http://localhost:8501
```

---

# 🐳 Run Using Docker

A pre-built Docker image is available on Docker Hub.

## Pull Docker Image

```bash
docker pull vahith05/student-engagement-system:latest
```

## Run Container

```bash
docker run -p 8501:8501 vahith05/student-engagement-system:latest
```

Open:

```
http://localhost:8501
```

---

# 📊 Generated Results

The system generates:

- Student detection results
- Engagement analysis
- Processed videos
- Statistical reports
- Visualization dashboards

---

# 🔮 Future Improvements

- 🎥 Real-time classroom monitoring
- 📷 Webcam-based analysis
- 👥 Advanced student tracking
- ☁️ Cloud deployment
- 🗄️ Database integration
- 📄 Automated PDF reports
- 🔐 Authentication system
- 📱 Mobile-friendly interface

---

# 🤝 Contributing

Contributions are welcome.

Steps:

1. Fork this repository

2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Add feature"
```

4. Push changes

```bash
git push origin feature-name
```

5. Create a Pull Request

---

# 👨‍💻 Author

**Vahith**

⭐ If you find this project useful, consider giving it a star!

---

# 📄 License

This project is developed for educational and research purposes.
```

