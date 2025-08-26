# Stateless Web APP Deployment on Kuberenetes

This repository contains Kubernetes manifests for deploying a statless web applicaition with Nginx

## How to Deploy 

1. **Clone this repository:**
    ```bash
    git clone https://github.com/koushik2316/stateless-web-app
    cd stateless-web-app
2. **Apply the Kubernetes manifests:**
    ```bash
    kubectl apply -f kubernetes-manifests/configmap.yaml
    kubectl apply -f kubernetes-manifests/deployment.yaml
    kubectl apply -f kubernetes-manifests/service.yaml
    kubectl apply -f kubernetes-manifests/hpa.yaml