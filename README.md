# 🚀 Dockerized Flask App

A stylish Python Flask web application containerized using Docker.
This project is built for practicing DevOps concepts like containerization, environment variables, and service orchestration using Docker Compose.

---

## 📸 Features

* 🌐 Clean UI using HTML & CSS
* 🐍 Python Flask backend
* 🐳 Docker support
* ⚙️ Environment variables
* ❤️ Health check endpoint
* 📦 Docker Compose support

---

## ▶️ Run Locally

pip install -r requirements.txt
python app.py

App will run on:
http://localhost:5000

---

## 🐳 Run with Docker

### 🔹 Build Image

docker build -t flask-docker-app .

### 🔹 Run Container

docker run -p 5000:5000 flask-docker-app

---

## 🚀 Run with Docker Compose

docker-compose up --build

👉 Open in browser:
http://localhost:5000

---

## 🔗 API Endpoints

/        → Home Page (UI)
/health  → Health Check

---

## ⚙️ Environment Variables

PORT → Application port (default: 5000)
ENV  → Environment mode (development/production)

---

## 💡 DevOps Concepts Used

* Docker containerization
* Docker Compose orchestration
* Environment variable handling
* Health check endpoint

---

## 👨‍💻 Author

Suraj Nagar
Aspiring DevOps Engineer 🚀

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
