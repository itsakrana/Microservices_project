# Microservices CI/CD Deployment using Docker, Kubernetes & Jenkins

## 📌 Project Overview
This project demonstrates the implementation of a full **CI/CD pipeline** for a **microservices-based application** using modern DevOps tools. It showcases containerization, automation, and deployment of multiple services in a Kubernetes cluster.

The pipeline automates:
- Code checkout from GitHub  
- Backend and frontend builds  
- Docker image creation and push to Docker Hub  
- Deployment to Kubernetes with proper service exposure  

---

## 🚀 Key Features
- **End-to-End CI/CD Pipeline**: Fully automated integration and delivery with Jenkins  
- **Containerization**: Dockerized frontend, backend, and MongoDB services  
- **Kubernetes Deployment**: Services deployed and managed in Minikube  
- **Automated Docker Registry**: Images pushed to Docker Hub automatically  
- **Service Exposure**: NodePort for frontend, ClusterIP for backend and database  
- **Multi-Service Architecture**: Frontend, Backend, MongoDB  

---

## 🛠️ Tools & Technologies
- **CI/CD**: Jenkins  
- **Containerization**: Docker  
- **Orchestration**: Kubernetes (Minikube)  
- **Version Control**: Git & GitHub  
- **Registry**: Docker Hub  

---

## 📊 Pipeline Stages

### CI Pipeline:
1. Checkout SCM  
2. Clone Code  
3. Build Backend & Frontend  
4. Docker Login  
5. Push Images to Docker Hub  

### CD Pipeline:
1. Deploy to Kubernetes  
2. Verify Deployment  

---


## 🔗 Links
- GitHub Repository: [https://github.com/itsakrana/Microservices_project.git](https://github.com/itsakrana/Microservices_project.git)  
- Docker Hub: `akrana2006/frontend` & `akrana2006/backend`  

---

## 💡 Learning Outcomes
- Hands-on experience in **building CI/CD pipelines**  
- Deep understanding of **Docker and Kubernetes orchestration**  
- Automated deployment workflow in a **microservices architecture**  
- Troubleshooting and scaling multi-service applications  
