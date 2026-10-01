# Kubernetes Demo Project

A beginner Kubernetes project demonstrating how to deploy a web application with MongoDB using Kubernetes.

## What I Learned

This project helped me understand the basics of:

* Kubernetes Deployments
* Kubernetes Services
* ConfigMaps
* Secrets
* Pod configuration
* Connecting a web application to MongoDB through a Kubernetes Service
* Exposing a web application using a NodePort Service

## Project Structure

```text
.
├── mongo.yaml
├── mongo-config.yaml
├── mongo-secrets.yaml
└── webapp.yaml
```

### MongoDB

`mongo.yaml` creates a MongoDB Deployment and Service.

### ConfigMap

`mongo-config.yaml` stores the MongoDB Service name used by the web application.

### Secret

`mongo-secrets.yaml` stores the MongoDB username and password used by the application.

### Web Application

`webapp.yaml` creates the web application Deployment and exposes it using a NodePort Service.

## Technologies

* Kubernetes
* MongoDB
* YAML

## Learning Resource

This project was created as a hands-on learning exercise while following the tutorial:

**Kubernetes Crash Course for Absolute Beginners [NEW]**

https://youtu.be/s_o8dwzRlu4?si=coL1WwRdOtKnQNw6

The project was used to practice and understand fundamental Kubernetes concepts.

## Note

This is a beginner learning project and is not intended to represent a production-ready Kubernetes deployment.
