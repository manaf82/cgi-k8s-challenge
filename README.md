# CGI Kubernetes Challenge

This project demonstrates deploying a simple web application on a Kubernetes cluster.

The application runs inside a container and displays a simple page:

Hello World

The deployment includes basic Kubernetes components such as:

- Deployment
- Service
- Ingress
- Horizontal Pod Autoscaler

---

## Architecture

Browser
↓
Ingress
↓
Service
↓
Kubernetes Deployment
↓
Pods (NGINX container)
↓
Hello World Web Page
