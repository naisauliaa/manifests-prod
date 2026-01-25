# Production Manifests

This repository contains the Kubernetes manifests required to deploy the **aplikasi-demo** in a production environment. Designed as the source of truth for GitOps workflows (such as ArgoCD), it includes a `deployment.yaml` to manage the application workload with high availability (2 replicas) and a `service.yaml` to expose the application via a NodePort service.
