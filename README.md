# 🐳 **DOCKER BASICS**  

Welcome to **Docker Basics**! 🚀 This repository showcases my journey with Docker, from basic containerization to more advanced Dockerized applications and microservices orchestration. Below is an overview of the projects along with documentation and step-by-step guides.

---

## 📂 **Projects Overview**

Here’s a list of the Docker projects included in this repository:

1. [**Docker Intro**](#docker-intro)
2. [**Deploying a Streamlit App in Docker on AWS EC2**](#deploying-a-streamlit-app-in-docker-on-aws-ec2)
3. [**Dockerized Streamlit Development Environment**](#dockerized-streamlit-development-environment)
4. [**Titanic Survival Predictor Containerized Streamlit App**](#titanic-survival-predictor-containerized-streamlit-app)
5. [**Containerized MySQL Agile & Efficient 🐬**](#containerized-mysql-agile--efficient-🐬)
6. [**Docker Volume Persistence: Bind Mounts with Linux Containers**](#docker-volume-persistence-bind-mounts-with-linux-containers)
7. [**Docker Bridge: Balancing Isolation & Connectivity**](#docker-bridge-balancing-isolation--connectivity)
8. [**Streamlit & PostgreSQL, Docked**](#streamlit--postgresql-docked)
9. [**Evidently AI Sets Sail in Docker**](#evidently-ai-sets-sail-in-docker)
10. [**Minikube with Docker on Windows**](#minikube-with-docker-on-windows)
11. [**Microservices Orchestration with Minikube and Kubernetes**](#microservices-orchestration-with-minikube-and-kubernetes)
12. [**Microservices Architecture using Docker Swarm**](#microservices-architecture-using-docker-swarm)
13. [**Bakery Foundation Example on Windows**](#bakery-foundation-example-on-windows)

---

## 📖 **Project Details**

### 🚀 **Docker Intro**

In this project, I started with the basic Docker operations by creating a **Hello World** Python application containerized with Docker.

#### Steps:
- Create a simple Python file to print **"Hello, World!"** using Docker.
- Containerize it with a Dockerfile.

For full instructions and resources, see the [documentation](#documentation--resources).

---

### 🔄 **Deploying a Streamlit App in Docker on AWS EC2**

This project involves deploying a **Streamlit** app in Docker on an **AWS EC2** instance.

#### Steps:
- Set up an EC2 instance and Docker environment.
- Deploy a Streamlit app in a Docker container.

---

### 🖥️ **Dockerized Streamlit Development Environment**

This project containerizes the **Streamlit** development environment for easier setup and deployment.

#### Features:
- Easily start developing Streamlit apps in Docker.
- Benefits of Docker in development environments.

---

### 🔍 **Titanic Survival Predictor Containerized Streamlit App**

Containerized a **Titanic Survival Predictor** machine learning model as a **Streamlit** app using Docker.

---

### 🐬 **Containerized MySQL Agile & Efficient**

A Docker setup to containerize **MySQL** for efficient storage and data management.

---

### 📦 **Docker Volume Persistence: Bind Mounts with Linux Containers**

Explored **Docker volumes** and **bind mounts** for data persistence in Linux containers.

---

### 🌉 **Docker Bridge: Balancing Isolation & Connectivity**

This project explores **Docker Bridge Networks** and how to balance container isolation with connectivity.

---

### 📊 **Streamlit & PostgreSQL, Docked**

This project shows how to use **PostgreSQL** with **Streamlit** in Docker.

---

### ⚙️ **Evidently AI Sets Sail in Docker**

Containerized **Evidently AI**, a tool for monitoring machine learning models in production.

---

### 🧱 **Minikube with Docker on Windows**

Explored using **Minikube** with Docker on **Windows** to simulate Kubernetes clusters for microservices.

---

### 🏗️ **Microservices Orchestration with Minikube and Kubernetes**

Set up **Minikube** and **Kubernetes** for orchestrating **microservices** using Docker.

---

### 🌀 **Microservices Architecture using Docker Swarm**

Implemented **microservices architecture** with **Docker Swarm** for distributed systems.

---

### 🍞 **Bakery Foundation Example on Windows**

A simple example of creating a **Dockerized bakery management system** using **Windows**.

---

## 📖 **Documentation & Resources**  

Here are some useful references for Docker:  
🔹 [Official Docker Documentation](https://docs.docker.com/)  
🔹 [Docker Desktop Guide](https://docs.docker.com/desktop/)  

---

## 🚀 **Deployment Guide**  

Follow these steps to deploy a basic application using Docker:

### 🔹 **Step 1: Install Docker and Python**  
1️⃣ Download and install **Docker Desktop** → [Get it here](https://www.docker.com/products/docker-desktop/)  
2️⃣ Ensure Docker is running.  
3️⃣ Install **Docker** and **Python** extensions in your development environment.  

---

### 🔹 **Step 2: Verify Installation**  
Before proceeding, confirm that **Docker** and **Python** are installed:  

✅ Check Docker version:  
```bash
docker --version 

### 🔹 Step 3: Build & Run Your Dockerized Application
🛠️ i) Build the Docker Image

Use the following command to build your Docker image:

```bash
docker build -t myapp .

### 🔍 ii) Verify the Image Creation
Check if your Docker image was created successfully:

```bash
docker images

### ▶️ iii) Run the Docker Container
Execute the container to print "Hello, World!" in the console:

```bash
docker run myapp

### 🎯 Conclusion
This guide provides a structured approach to running your first Dockerized Python application. 🐳✨

🔹 Next Steps: Explore Docker volumes, networking, and multi-container applications! 💡

🚀 Happy Docking! ⚓🌊


