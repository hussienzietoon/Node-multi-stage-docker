Node.js Multi-Stage Docker App 🚀

This is a simple Node.js application that uses a **multi-stage Docker build** for optimization.

## 📌 Features

- A basic Express.js server
- Dockerized with multi-stage builds
- Lightweight production image

## 🛠 Setup

### **1️⃣ Clone the Repository**

```sh
git clone git@github.com:hussienzietoon/Node-multi-stage-docker.git
cd Node-multi-stage-docker
```

### **2️⃣ Build and Run with Docker**

```sh
docker build -t node-multi-stage .
docker run -p 3000:3000 node-multi-stage
```
