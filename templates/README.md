# My App GitOps Repository

This repository contains the Helm chart and Kubernetes manifests for deploying `SIMPLEDEMO` to a Kubernetes cluster using ArgoCD.

## Structure
- **Chart.yaml**: Contains metadata for the Helm chart.
- **values.yaml**: Default configuration values for the Helm chart.
- **templates/deployment.yaml**: Kubernetes deployment manifest template.
- **templates/service.yaml**: Kubernetes service manifest template.

## Deploying Using Helm
To deploy the application using Helm, run the following commands:

```bash
helm install my-app ./ --namespace default