# Bookinfo Microservice - Config Repository

This repository contains the GitOps configuration for the Bookinfo microservice using ArgoCD, Kustomize, and Helm.

## Project Structure
```
├── base/
│   ├── kustomization.yaml
│   ├── deployment.yaml
│   └── service.yaml
├── overlays/
│   ├── dev/
│   │   ├── kustomization.yaml
│   │   └── values.yaml
│   └── prod/
│       ├── kustomization.yaml
│       └── values.yaml
├── argocd/
│   └── app-of-apps.yaml
└── README.md
```

## Components
1. Base Configuration
   - Common Kustomize resources
   - Base Helm values

2. Environment Overlays
   - Development environment configuration
   - Production environment configuration

3. ArgoCD Configuration
   - Application of applications
   - Environment-specific ArgoCD apps

## Usage
1. Clone the repository
2. Configure ArgoCD
3. Deploy using ArgoCD

## License
MIT
