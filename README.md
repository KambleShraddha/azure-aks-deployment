# Kubernetes (AKS-ready) with Helm + Observability

Run on local kind/minikube or AKS later. Includes Deployment, Service, Ingress, Helm chart, and monitoring notes.

## Local quickstart
```
# kind create cluster   OR   minikube start
kubectl apply -f k8s/
# or helm install mywebapp ./helm/mywebapp
```
