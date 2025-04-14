# Kubernetes Cluster with Minikube

This project demonstrates the deployment and management of applications in a Kubernetes cluster using Minikube. The following steps outline how to set up Minikube, deploy an app, expose it using a service, and scale the deployments.

## Objective

The objective of this project is to build and manage a local Kubernetes cluster using Minikube, deploy an app, and manage its lifecycle using kubectl.

## Tools Used

- **Minikube**: A tool to run Kubernetes clusters locally.
- **kubectl**: A command-line tool for interacting with Kubernetes clusters.
- **Docker**: Container platform used for creating and running the application containers.

## Steps to Reproduce

### 1. Install Minikube and Start the Cluster

- Follow the Minikube installation guide: https://minikube.sigs.k8s.io/docs/ 
- Start Minikube by running the following command:
  ```bash
  minikube start
