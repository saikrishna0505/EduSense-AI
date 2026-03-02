# 🎓 EduSense AI  
### Intelligent Classroom Engagement & Emotion Analytics Platform

---

## 📌 Overview

**EduSense AI** is a next-generation classroom intelligence system that leverages **Artificial Intelligence, Computer Vision, and Real-Time Analytics** to measure student engagement and emotional responses during live sessions.

The platform analyzes webcam video streams to generate actionable insights for educators through a dynamic dashboard, helping improve teaching strategies and learning outcomes.

EduSense AI transforms traditional classrooms into **data-driven smart learning environments**.

---

## 🚀 Core Features

- 🎥 Real-time video stream analysis  
- 😊 Emotion detection (Happy, Neutral, Focused, Confused, etc.)  
- 👁️ Attention tracking & face detection  
- 📊 Engagement scoring engine  
- 🧑‍🏫 Teacher dashboard with live analytics  
- 👨‍🎓 Student participation interface  
- 📡 RESTful API using FastAPI  
- 🌐 Modern frontend built with React + Vite  
- 🧠 Deep Learning models (Vision Transformers / CNNs)  
- 🧩 Modular & scalable architecture  

---

## 🏗️ System Architecture

```
Student Webcam
      ↓
Video Stream Processing
      ↓
AI Model (Emotion + Attention Detection)
      ↓
Backend API (FastAPI)
      ↓
Analytics Engine
      ↓
Teacher Dashboard (React)
```

---

## 🛠️ Technology Stack

### 🔹 Backend
- Python
- FastAPI
- OpenCV
- PyTorch / TensorFlow
- Hugging Face Transformers
- Uvicorn

### 🔹 Frontend
- React
- Vite
- Axios
- Chart.js / Recharts
- Tailwind CSS (Optional)

### 🔹 AI / ML
- Vision Transformer (ViT)
- Face Detection Models
- Emotion Classification Models
- Engagement Scoring Algorithm

---

## 📂 Project Structure

```
EduSense-AI/
│
├── backend/
│   ├── app/
│   │   ├── main.py
│   │   ├── routes/
│   │   ├── models/
│   │   ├── services/
│   │   └── utils/
│   ├── requirements.txt
│   └── config.py
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.jsx
│   ├── package.json
│   └── vite.config.js
│
├── models/
│   └── pretrained_models/
│
├── README.md
└── .gitignore
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/saikrishna0505/EduSense-AI.git
cd EduSense-AI
```

---

### 2️⃣ Backend Setup

```bash
cd backend
python -m venv venv
```

Activate virtual environment:

- **Windows**
```bash
venv\Scripts\activate
```

- **Mac/Linux**
```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the backend server:

```bash
uvicorn app.main:app --reload
```

Backend URL:

```
http://127.0.0.1:8000
```

Swagger API Docs:

```
http://127.0.0.1:8000/docs
```

---

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend URL:

```
http://localhost:5173
```

---

## 📊 Engagement Scoring Model (Example)

```
Engagement Score =
(Attention Score × 0.5) +
(Emotion Confidence × 0.3) +
(Participation Activity × 0.2)
```

### Score Classification
- 🔴 0–40 → Low Engagement  
- 🟡 41–70 → Moderate Engagement  
- 🟢 71–100 → High Engagement  

---

## 📈 How It Works

1. Student joins session.
2. Webcam captures live feed.
3. AI model processes frames.
4. Emotion & attention are detected.
5. Engagement score is computed.
6. Data is pushed to backend.
7. Dashboard updates in real-time.

---



## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Push to your branch
5. Open a Pull Request

---

## 🛡️ License

This project is licensed under the MIT License.



---

## 📌 GitHub Topics

```
ai
computer-vision
edtech
emotion-detection
engagement-analysis
fastapi
react
machine-learning
education-analytics
```
