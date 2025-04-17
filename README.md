# 323-prac6c

### required tools

Git

Visual Studio code

Node.js

Docker

Kubernetes

Kubernetes CLI (kubectl)

Docker CLI

### steps

#### 1. verify application status
   <code>kubectl get pods</code>
   <code>kubectl get services</code>

#### 2. access the service locally
   <code>kubectl port-forward service/node-web-service 8081:3000</code>

Navigate to <code>http://localhost:8081</code>
