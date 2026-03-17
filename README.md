# 🚀 DevOps Project: Docker + Kubernetes Deployment

## 📌 Project Overview

This project demonstrates a complete DevOps workflow where a simple HTML application is containerized using Docker and deployed on Kubernetes running on AWS EC2.

---

## 🛠️ Technologies Used

* Docker
* Kubernetes (KOPS)
* AWS EC2
* GitHub

---

## 📂 Project Structure

```
myapp/
│── index.html
│── Dockerfile
│── replicaset.yaml
│── service.yaml
```

---

## 🐳 Docker Setup

### Build Docker Image

```
docker build -t abhipsa-devops/myapp:v1 .
```

### Push to DockerHub

```
docker push abhipsa-devops/myapp:v1
```

---

## ☸️ Kubernetes Deployment

### Create ReplicaSet

```
kubectl apply -f replicaset.yaml
```

### Create Service

```
kubectl apply -f service.yaml
```

---

## 🌐 Access Application

Check services:

```
kubectl get svc
```

Open the **EXTERNAL-IP** in your browser to v
