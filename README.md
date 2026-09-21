\# Kubernetes Production Demo 🚀



A production-style DevOps project demonstrating containerization, CI/CD,

Kubernetes deployment, autoscaling, health checks, configuration management,

Ingress, Prometheus monitoring, and Grafana observability.



\## 🏗️ Architecture



Developer

&#x20;  ↓

GitHub

&#x20;  ↓

GitHub Actions

&#x20;  ↓

Docker Build

&#x20;  ↓

Docker Hub

&#x20;  ↓

Kubernetes

&#x20;  ├── Namespace

&#x20;  ├── Deployment

&#x20;  ├── Rolling Update

&#x20;  ├── ConfigMap

&#x20;  ├── Secret

&#x20;  ├── Liveness Probe

&#x20;  ├── Readiness Probe

&#x20;  ├── Service

&#x20;  ├── Ingress

&#x20;  └── HPA

&#x20;       ↓

&#x20;  Application

&#x20;       ↓

Prometheus

&#x20;       ↓

Grafana Dashboard



\## 🛠️ Technologies



\- Docker

\- Docker Hub

\- GitHub

\- GitHub Actions

\- Kubernetes

\- Kubernetes HPA

\- Kubernetes Ingress

\- ConfigMap

\- Secret

\- Prometheus

\- Grafana

\- NGINX

\- YAML

\- PowerShell / Git Bash



\## 📦 Docker



Build the application:



```bash

docker build -t k8s-production-demo:v1 .

