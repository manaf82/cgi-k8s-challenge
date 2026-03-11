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

Cluster provisioning

The cluster is created using Kind (Kubernetes in Docker).
The configuration is defined in kind-cluster.yaml.

Application deployment

The application is deployed using Kubernetes manifests located in the k8s/ directory.

kubectl apply -f k8s/

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
