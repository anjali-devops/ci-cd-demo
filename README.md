# 🚀 End-to-End CI/CD Pipeline using AWS, Docker & GitHub Actions

## 📌 Overview
This project demonstrates an end-to-end CI/CD pipeline for a containerized application using GitHub Actions, Docker, and AWS.

---

## 🧰 Tech Stack
- AWS (EC2, IAM)
- Docker
- GitHub Actions
- Linux

---

## 🛠️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/anjali-devops/ci-cd-demo.git
cd ci-cd-demo
```

---

### 2️⃣ Build Docker Image

```bash
docker build -t ci-cd-demo .
```

---

### 3️⃣ Run the Application

```bash
docker run -d -p 80:80 ci-cd-demo
```

Access at: http://localhost

---

### 4️⃣ Configure GitHub Secrets

Go to:
Settings → Secrets → Actions

Add:
- DOCKER_USERNAME
- DOCKER_PASSWORD
- AWS_ACCESS_KEY_ID
- AWS_SECRET_ACCESS_KEY

---

### 5️⃣ Trigger CI/CD Pipeline

```bash
git add .
git commit -m "trigger pipeline"
git push origin main
```

---

## 📉 Key Achievements
- Reduced deployment steps from 8 → 1
- Automated full CI/CD workflow
- Improved deployment consistency

---

## 👩‍💻 Author
Anjali Damisetty
