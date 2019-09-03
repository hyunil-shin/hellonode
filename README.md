# Hello Node
This is a very basic Hello World application written with Node.

It includes a `Dockerfile` for building a Docker image with the application, and a `Jenkinsfile` that defines a build pipeline for it.

https://getintodevops.com



# Deploy to Kubernetes cluster
```
kubectl apply -f deployment.yaml
kubectl get pods
kubectl apply -f service.yaml
kubectl get services
```
