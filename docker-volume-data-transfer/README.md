# Docker Volume Data Transfer 🚀

## 📌 Overview
This project demonstrates how to extract data from a Docker volume and use it inside another container using Jenkins pipeline automation.

---

## 🚀 Workflow
1. Create local directory for storing files
2. Inspect Docker volume
3. Extract volume mount path
4. Copy data from volume to local directory
5. Build Docker image using copied data
6. Run container

---

## 🛠️ Tech Stack
- Docker
- Jenkins
- Linux (Shell)
- jq (JSON parsing)

---

## 📦 Key Features
- Docker volume inspection
- Data extraction from volumes
- Temporary container usage
- Automated workflow using Jenkins

---

## 📂 Project Structure
```
Dockerfile
Jenkinsfile
jar-file/
```

---

## 📌 Key Learnings
- Working with Docker volumes
- Extracting container data
- Using temporary containers for data transfer
- Advanced Jenkins pipeline scripting

---

## ⚠️ Prerequisites
- Docker installed
- jq installed (for JSON parsing)

---

## 🚀 Future Improvements
- Automate upload to cloud storage (S3)
- Integrate with Kubernetes
