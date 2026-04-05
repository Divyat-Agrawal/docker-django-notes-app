# 🚀 Dockerized Django Notes App

<p align="center">
  <img src="https://img.shields.io/badge/Docker-Multi--Container-blue?logo=docker">
  <img src="https://img.shields.io/badge/DevOps-Project-success">
  <img src="https://img.shields.io/badge/AWS-EC2-orange?logo=amazonaws">
</p>

<p align="center">
  <b>Containerized a full-stack application & deployed it on AWS EC2</b>
</p>

---

## 🧠 Architecture


flowchart LR
User 🌐 --> Nginx ⚡ --> Django 🐍 --> MySQL 🗄️


---

## ⚡ What I Did (DevOps Work)

* 🐳 Containerized Django using Dockerfile
* ⚙️ Designed multi-container setup (Nginx + Django + MySQL)
* 🌐 Configured Nginx as reverse proxy
* 💾 Added volume for persistent DB storage
* 🔐 Used `.env` for configuration
* ❤️ Implemented health checks & dependencies
* ☁️ Deployed application on AWS EC2 instance
* 🧩 Resolved real issues (port conflicts, DB readiness)

---

## 🚀 Run Locally

```bash
git clone https://github.com/Divyat-Agrawal/docker-django-notes-app.git
cd docker-django-notes-app
docker-compose up --build
```

👉 Access: http://localhost:8080

---

## ☁️ Deployment (AWS EC2)

* Launched EC2 instance
* Installed Docker & Docker Compose
* Cloned repository and ran containers
* Exposed port **8080** for public access

---

## 🧠 Key DevOps Concepts

`Dockerfile` • `Docker Compose` • `Networking` • `Volumes` • `Env Variables` • `Reverse Proxy`

---

