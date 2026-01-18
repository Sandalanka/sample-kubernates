# 🚀 Node.js Cluster: Docker & Kubernetes

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-326ce5?style=for-the-badge&logo=kubernetes&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)

A production-ready demonstration of containerizing a Node.js Express API and orchestrating it within a Kubernetes cluster. This project showcases auto-healing, scaling, and load balancing.

---

## 🏗 System Architecture

How the traffic flows from the internet to your Node.js pods:



---

## 🌟 Key Features

- **Express.js API:** Lightweight and high-performance backend.
- **Dockerized:** Multi-stage builds for small, secure images.
- **K8s Deployment:** Manages 3 replicas with rolling update support.
- **Self-Healing:** Kubernetes automatically restarts containers that fail health checks.
- **Load Balancing:** Service (NodePort) distributes traffic across all running pods.

---

## 🛠 Prerequisites

Ensure you have the following installed:
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [Minikube](https://minikube.sigs.k8s.io/docs/start/) or [Kind](https://kind.sigs.k8s.io/)
- [kubectl](https://kubernetes.io/docs/tasks/tools/)

---

## 🚀 Getting Started

### 1. Clone & Local Test
```bash
git clone [https://github.com/your-username/node-k8s-project.git](https://github.com/your-username/node-k8s-project.git)
cd node-k8s-project/app
npm install
npm start