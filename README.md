# Online Ticket Booking Fullstack Application on Kubernetes

This is a minimal project structure for deploying a React (Frontend) and Node/Express (Backend) application using Docker and Kubernetes.

## 📂 Project Structure
- **frontend** → React app Dockerfile
- **backend** → Node/Express app Dockerfile
- **k8s-manifests** → Kubernetes Deployment & Service YAML files

## 🚀 Deployment
Apply all manifests:
```bash
kubectl apply -f k8s-manifests/
```
