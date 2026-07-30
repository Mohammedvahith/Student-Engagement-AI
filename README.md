# 🎓 AI-Powered Student Engagement System

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-Web_App-red?style=for-the-badge&logo=streamlit)
![YOLO](https://img.shields.io/badge/YOLO-Ultralytics-green?style=for-the-badge)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep_Learning-orange?style=for-the-badge&logo=tensorflow)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer_Vision-blue?style=for-the-badge&logo=opencv)
![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?style=for-the-badge&logo=docker)

</p>

---

## 📖 Overview

The **AI-Powered Student Engagement System** is a computer vision application designed to analyze classroom videos and evaluate student engagement using deep learning techniques.

The system detects students, processes classroom interactions, and generates engagement insights through an intuitive **Streamlit** web application. It combines **YOLO**, **TensorFlow**, and **OpenCV** to automate video analysis and present meaningful analytics for educators.

---

## ✨ Key Features

- 🎥 Upload classroom videos
- 🤖 Student detection using **YOLO**
- 🧠 AI-based engagement analysis
- 📊 Interactive analytics dashboard
- 📈 Visual insights and statistics
- ⚡ Automated video processing pipeline
- 💻 Modern Streamlit interface
- 🐳 Docker support for easy deployment

---

# 📷 Application Preview


## Home Page

<img width="1919" height="912" alt="1" src="https://github.com/user-attachments/assets/4ff8e135-a2c3-4572-a1eb-59f9b4370eeb" />

## Video Upload

<img width="1919" height="911" alt="2" src="https://github.com/user-attachments/assets/b00623b8-4a1e-464a-8013-e35c6458caec" />

## Analytics Dashboard

<img width="1919" height="909" alt="3" src="https://github.com/user-attachments/assets/b21cbb99-12f8-4cba-94f5-f0b5f1fa2db2" />

<img width="1919" height="911" alt="4" src="https://github.com/user-attachments/assets/8237207f-436e-46d4-9e43-45bacac1d83d" />

## Processed Output 

<img width="1919" height="905" alt="5" src="https://github.com/user-attachments/assets/ad588feb-a7bf-4dc8-9773-17f0f1cf27fd" />

---

# 🏗️ System Workflow

```text
                Classroom Video
                        │
                        ▼
                Upload to Streamlit
                        │
                        ▼
             Video Frame Extraction
                        │
                        ▼
          Student Detection (YOLO Model)
                        │
                        ▼
         Engagement Feature Extraction
                        │
                        ▼
           AI-Based Engagement Analysis
                        │
                        ▼
            Analytics & Visual Reports
                        │
                        ▼
                User Dashboard
```

---

# 🛠️ Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python 3.10 |
| Frontend | Streamlit |
| Deep Learning | TensorFlow |
| Object Detection | YOLO (Ultralytics) |
| Computer Vision | OpenCV |
| Data Processing | NumPy, Pandas |
| Visualization | Matplotlib |
| Deployment | Docker |

---

# 📂 Project Structure

```text
student_engagement_system/
│
├── analytics/
├── config/
├── models/
├── outputs/
├── processing/
├── tracking/
├── utils/
│
├── app.py
├── requirements.txt
├── Dockerfile
├── docker-compose.yaml
├── .dockerignore
├── .gitignore
└── README.md
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/student_engagement_system.git

cd student_engagement_system
```

Create a virtual environment

```bash
python -m venv .venv
```

Activate the environment

### Windows

```bash
.venv\Scripts\activate
```

### Linux / macOS

```bash
source .venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Application

```bash
streamlit run app.py
```

Open your browser:

```
http://localhost:8501
```

---

# 🐳 Run using Docker

A pre-built Docker image is available on Docker Hub.

```bash
docker pull vahith05/student-engagement-system:latest

docker run -p 8501:8501 vahith05/student-engagement-system:latest.
```

---

# 📊 Output

The system provides:

- Student detection results
- Engagement analysis
- Visual analytics
- Performance statistics
- Processed outputs
- Interactive dashboard

---

# 🔮 Future Enhancements

- 🎯 Real-time webcam support
- 👥 Multi-person engagement tracking
- 📈 Advanced analytics dashboard
- ☁️ Cloud deployment
- 🗄️ Database integration
- 📄 Export reports (PDF/Excel)
- 🔐 User authentication
- 📱 Mobile-friendly interface

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 👨‍💻 Author

**Vahith**

If you found this project useful, consider giving it a ⭐ on GitHub!

---

# 📄 License

This project is developed for educational and research purposes.

