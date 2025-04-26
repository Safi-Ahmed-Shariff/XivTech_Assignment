Hello World Kubernetes Assignment

Project Overview
A simple "Hello World" application deployed using a custom NGINX Docker image on a local Kind Kubernetes cluster.

Steps
Created a custom NGINX Docker image serving a static HTML file.
Set up a local Kubernetes cluster using Kind.
Deployed the application using Kubernetes Deployment and Service manifests.
Exposed the app via NodePort (localhost:30007) and also accessed it via port-forwarding (localhost:8080) for demonstration.
Recorded a demo video showcasing the full setup.

Repository Structure

- app/index.html
- docker/Dockerfile
- k8s/deployment.yaml, service.yaml
- demo/video.mp4
