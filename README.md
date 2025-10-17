Simple Kubernetes Learning Project
This is a straightforward educational project designed to help you get familiar with the basics of Kubernetes. The project includes a lightweight application that returns the current date and time with each curl request.
Getting Started
To run the project, clone the repository and execute the following commands:


kubectl apply -f node-app-deployment.yaml
kubectl apply -f node-app-service.yaml
kubectl apply -f postgres-deployment.yaml
kubectl apply -f postgres-secret.yaml
kubectl apply -f postgres-service.yaml

This project is ideal for learning and experimenting with Kubernetes, allowing you to gain hands-on experience with deploying applications, managing services, and handling secrets in a Kubernetes environment.


<image-card alt="Kubernetes Logo" src="https://kubernetes.io/images/favicon.png" ></image-card>
