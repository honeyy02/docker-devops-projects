# Docker Runtime with Volume 🚀

## 📌 Overview
This project demonstrates running a Docker container with persistent storage using Docker volumes, along with Jenkins pipeline automation.

---

## 🚀 Features
- Docker image build using Maven
- Persistent storage using Docker volume
- Container lifecycle management
- Automated execution using Jenkins pipeline

---

## 🛠️ Tech Stack
- Docker
- Jenkins
- Maven
- Java

---

## 📂 Project Structure
```
Dockerfile
Jenkinsfile
```

---

## 🔄 Workflow

1. Jenkins checks Docker installation  
2. Source code is checked out  
3. Docker image is built  
4. Docker volume is created  
5. Existing container is stopped and removed  
6. New container is started with volume attached  

---

## 📦 Docker Volume
- Volume Name: `my-volume`
- Mounted Path: `/app/target`

👉 Ensures build artifacts (JAR file) persist across container restarts

---

## 🌐 Access Application
```
http://localhost:8081
```

---

## 📌 Key Learnings
- Docker volume usage for persistent storage  
- Managing container lifecycle (stop/remove/run)  
- Integrating Docker workflows with Jenkins  

---

## 🚀 Future Improvements
- Use Docker Compose  
- Add health checks  
- Deploy to Kubernetes  
