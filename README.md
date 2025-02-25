# Node.js Multi-Stage Docker App 🚀

This is a simple Node.js application that uses a **multi-stage Docker build** for optimization.

## 📌 Features
- A basic Express.js server
- Dockerized with multi-stage builds
- Lightweight production image

## 🛠 Setup

### **1️⃣ Clone the Repository**

git clone https://github.com/YOUR_USERNAME/nodejs-multi-stage-docker-app.git
cd nodejs-multi-stage-docker-app

### ** 2️⃣ Build and Run with Docker

docker build -t node-multi-stage .
docker run -p 3000:3000 node-multi-stage