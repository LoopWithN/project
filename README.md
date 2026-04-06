# 🚀 Microservices on Self-Managed Kubernetes

![Kubernetes](https://img.shields.io/badge/Kubernetes-Cluster-blue)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue)
![Jenkins](https://img.shields.io/badge/Jenkins-CI/CD-red)



## 📌 Project Overview

This project demonstrates a complete **DevOps pipeline** where a Node.js application is containerized using Docker and deployed on a **self-managed Kubernetes cluster (kubeadm)** on AWS EC2.



## 🧱 Architecture Diagram
    +-------------+
    |   GitHub    |
    +-------------+
           |
           v
    +-------------+
    |   Jenkins   |
    |   (CI/CD)   |
    +-------------+
           |
           v
    +-------------+
    |   Docker    |
    |  (Build)    |
    +-------------+
           |
           v
    +------------------+
    |   Docker Hub     |
    +------------------+
           |
           v
    +------------------+
    |   Kubernetes     |
    | (kubeadm cluster)|
    +------------------+
           |
           v
    +------------------+
    |     Users 🌐     |
    +------------------+




    
---

## ⚙️ Tech Stack

- ☸️ Kubernetes (kubeadm)
- 🐳 Docker
- ⚙️ Jenkins (CI/CD)
- ☁️ AWS EC2
- 🌐 Node.js
- 🔗 GitHub
- 🌐 Flannel (CNI)


---

## 🚀 Features

- Automated CI/CD pipeline  
- Containerized application  
- Self-managed Kubernetes cluster  
- Networking using Flannel  
- Exposed via NodePort  

---

## 🛠 Implementation Steps

1. Developed Node.js application  
2. Created Dockerfile & built image  
3. Pushed image to Docker Hub  
4. Set up Kubernetes cluster using kubeadm  
5. Applied Deployment & Service YAML  
6. Exposed application using NodePort  

---

## 📸 Project Screenshots

### 🔹 Application Running
<img width="1920" height="1020" alt="Screenshot 2026-04-04 151731" src="https://github.com/user-attachments/assets/26bafa7c-34ee-46ee-8f14-1cec8198087e" />


### 🔹 Kubernetes Pods
<img width="1920" height="1020" alt="Screenshot 2026-04-02 115913" src="https://github.com/user-attachments/assets/2018159c-750b-46c3-9fa5-2b5db286e256" />


### 🔹 Jenkins Pipeline
<img width="1920" height="1020" alt="Screenshot 2026-04-06 212836" src="https://github.com/user-attachments/assets/687a9d8a-b84b-4933-8f23-4fabeb43031c" />


## 🌐 Access Application
http://13.53.130.130:31136/

