# AI-BankApp – DevOps & Kubernetes

A hands-on DevOps project where I practiced deploying an application using Docker, Kubernetes and Kind.

## What I Practiced

- Docker
- Kubernetes
- Kind Cluster
- Kubernetes Deployments
- Services
- ConfigMap & Secrets
- MySQL
- Persistent Volume (PV)
- Persistent Volume Claim (PVC)
- Basic Kubernetes Troubleshooting

## Kubernetes Setup

- 1 Control Plane
- 2 Worker Nodes
- BankApp
- MySQL
- Ollama

## Kubernetes Commands Practiced

```bash
kubectl get nodes
kubectl get pods -n bankapp
kubectl get svc -n bankapp
kubectl get pv,pvc -n bankapp
kubectl get configmap,secrets -n bankapp
Project Structure
AI-BankApp-DevOps/
├── k8s/
├── setup-k8s/
├── Dockerfile
└── README.md
Project Status

Hands-on Kubernetes and Kind setup completed as part of my DevOps learning journey.

The project also helped me practice Kubernetes configuration, persistent storage, services and troubleshooting.

Learning Outcome

Through this project I learned the basics of:

Containerization with Docker
Kubernetes cluster setup with Kind
Deployments and Services
Storage using PV and PVC
ConfigMaps and Secrets
Basic Kubernetes troubleshooting
