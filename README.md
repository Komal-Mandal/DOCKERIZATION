# DOCKERIZATION

# 📢 Flask Hello World App - Dockerized

This is a simple Flask project that runs a "Hello, World!" web app.
The app is fully Dockerized using a Dockerfile and docker-compose.yml for easy setup and deployment.

## 🐳 What’s Inside?


✅ A basic Flask app that returns "Hello, World!" on the homepage

✅ Dockerfile to build and containerize the Flask app

✅ Docker Compose file for easy multi-container management


# 📁 Project Structure

## ├── table.py 
Python script to print the table

## ├── Dockerfile 
 Docker build instructions

## └── docker-compose.yml 
Optional: Compose for running the container

# 🚀 How to Run

## 🔧 Prerequisites

- Docker must be installed on your system (Docker Desktop is recommended).

- Docker Compose is optional but useful for running multi-container setups easily.

## ▶️ Run with Docker

### Clone the repo
- git clone https://github.com/Komal-Mandal/DOCKERIZATION

- cd DOCKERIZATION

### Build the Docker image
- docker build -t hello-app .

### Run the container
- docker run hello-app

### ▶️ Run with Docker Compose
- docker compose up 

