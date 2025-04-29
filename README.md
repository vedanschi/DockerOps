# 🐳 **DOCKER BASICS**

Welcome to **Docker Basics**! 🚀 This repository showcases my journey with Docker — from basic containerization to advanced Dockerized applications and microservices orchestration. Below is an overview of the projects, along with documentation and step-by-step guides.

---

## 📂 **Projects Overview**

Here’s a list of the Docker projects included in this repository:

1. [**Docker Intro**](#-docker-intro)
2. [**Deploying a Streamlit App in Docker on AWS EC2**](#-deploying-a-streamlit-app-in-docker-on-aws-ec2)
3. [**Dockerized Streamlit Development Environment**](#-dockerized-streamlit-development-environment)
4. [**Titanic Survival Predictor Containerized Streamlit App**](#-titanic-survival-predictor-containerized-streamlit-app)
5. [**Containerized MySQL Agile & Efficient 🐬**](#-containerized-mysql-agile--efficient-)
6. [**Docker Volume Persistence: Bind Mounts with Linux Containers**](#-docker-volume-persistence-bind-mounts-with-linux-containers)
7. [**Docker Bridge: Balancing Isolation & Connectivity**](#-docker-bridge-balancing-isolation--connectivity)
8. [**Streamlit & PostgreSQL, Docked**](#-streamlit--postgresql-docked)
9. [**Evidently AI Sets Sail in Docker**](#-evidently-ai-sets-sail-in-docker)
10. [**Minikube with Docker on Windows**](#-minikube-with-docker-on-windows)
11. [**Microservices Orchestration with Minikube and Kubernetes**](#-microservices-orchestration-with-minikube-and-kubernetes)
12. [**Microservices Architecture using Docker Swarm**](#-microservices-architecture-using-docker-swarm)
13. [**Bakery Foundation Example on Windows**](#-bakery-foundation-example-on-windows)

---

## 📖 **Project Details**

### 🚀 **Docker Intro**
- Created a simple Python file that prints **"Hello, World!"**.
- Containerized it with Docker.

---

### 🔄 **Deploying a Streamlit App in Docker on AWS EC2**
- Set up an EC2 instance.
- Deployed a Streamlit app inside a Docker container.

---

### 🖥️ **Dockerized Streamlit Development Environment**
- Dockerized the Streamlit development environment.
- Simplified local development setup.

---

### 🔍 **Titanic Survival Predictor Containerized Streamlit App**
- Deployed a machine learning model predicting Titanic survival inside a Docker container with Streamlit UI.

---

### 🐬 **Containerized MySQL Agile & Efficient**
- Containerized a MySQL database for fast, agile development and efficient data storage.

---

### 📦 **Docker Volume Persistence: Bind Mounts with Linux Containers**
- Used Docker volumes and bind mounts to persist container data.

---

### 🌉 **Docker Bridge: Balancing Isolation & Connectivity**
- Explored Docker bridge networks to balance isolation and communication between containers.

---

### 📊 **Streamlit & PostgreSQL, Docked**
- Connected Streamlit with PostgreSQL, both containerized with Docker.

---

### ⚙️ **Evidently AI Sets Sail in Docker**
- Containerized **Evidently AI** for ML model monitoring.

---

### 🧱 **Minikube with Docker on Windows**
- Simulated Kubernetes clusters with Minikube and Docker on Windows.

---

### 🏗️ **Microservices Orchestration with Minikube and Kubernetes**
- Orchestrated microservices using Kubernetes and Docker containers.

---

### 🌀 **Microservices Architecture using Docker Swarm**
- Implemented microservices using Docker Swarm mode.

---

### 🍞 **Bakery Foundation Example on Windows**
- Developed a Dockerized bakery management app example on Windows OS.

---

## 📖 **Documentation & Resources**

Here are some useful references for Docker:  
🔹 [Official Docker Documentation](https://docs.docker.com/)  
🔹 [Docker Desktop Guide](https://docs.docker.com/desktop/)

---

## 🚀 **Deployment Guide**

Follow these steps to deploy a basic Dockerized Python application:

### 🔹 **Step 1: Install Docker and Python**
1. Download and install [Docker Desktop](https://www.docker.com/products/docker-desktop/).
2. Ensure Docker service is running.
3. Install **Docker** and **Python** extensions in your development environment.

---

### 🔹 **Step 2: Verify Installation**

Check if **Docker** and **Python** are correctly installed:

```bash
docker --version
```

```bash
python --version
```

If both commands return valid version numbers, you're ready to go! 🎉

---

### 🔹 **Step 3: Build & Run Your Dockerized Application**

#### 🛠️ Build the Docker Image

```bash
docker build -t myapp .
```

#### 🔍 Verify the Image Creation

```bash
docker images
```

#### ▶️ Run the Docker Container

```bash
docker run myapp
```

---

## 🎯 **Conclusion**

This repository provides a structured walkthrough for setting up and deploying applications using Docker — starting from simple projects to complex orchestration. 🐳✨

🔹 **Next Steps**: Dive deeper into volumes, networking, multi-container setups, and Kubernetes! 💡

🚀 **Happy Docking!** ⚓🌊
