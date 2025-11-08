# ☸️ Azure AKS Deployment (Helm + Monitoring)

![Kubernetes](https://img.shields.io/badge/Kubernetes-AKS-blue)
![Helm](https://img.shields.io/badge/Helm-Charts-0F1689)
![Monitoring](https://img.shields.io/badge/Monitoring-Prometheus%2FGrafana-4CAF50)
![Azure](https://img.shields.io/badge/Cloud-Azure-0078D4)
![Status](https://img.shields.io/badge/Status-Ready-success)

## 📘 Project Overview
This project simulates a **Kubernetes-based deployment pipeline** for a containerized web application on **Azure Kubernetes Service (AKS)**.  
It uses **Helm** for application deployment and integrates **Prometheus & Grafana** for monitoring.

### Key Objectives
- Deploy a sample app to Kubernetes cluster (works on *Minikube*, *kind*, or *AKS*)
- Package the app using Helm
- Set up observability with Prometheus & Grafana

---

## 🧰 Tech Stack
| Tool | Purpose |
|------|----------|
| **Kubernetes (AKS)** | Container orchestration |
| **Helm** | Application packaging and release management |
| **Prometheus** | Metrics collection |
| **Grafana** | Visualization and alerting |
| **Docker** | Container image base |
| **GitHub** | Source version control |

---

## ⚙️ Architecture Diagram

```mermaid
graph TD
    A[Docker Image] --> B[Helm Chart]
    B --> C[Kubernetes Cluster (AKS / kind)]
    C --> D[Deployment + Service + Ingress]
    D --> E[Prometheus Metrics]
    E --> F[Grafana Dashboard]
```
