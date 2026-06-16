\# Deploying a New Microservice to AWS EKS



\## Step 1



Developer pushes code to GitHub.



\## Step 2



GitHub Actions pipeline starts.



Pipeline performs:



\* Build Docker Image

\* Run Tests

\* Push Image to DockerHub or Amazon ECR



\## Step 3



Deploy to Kubernetes.



Deployment YAML:



\* Deployment

\* Service

\* ConfigMap

\* Secret



\## Step 4



AWS EKS schedules Pods.



Pods run across worker nodes.



\## Step 5



Ingress exposes application.



Users access application through Load Balancer.



\## Step 6



Monitoring



Use:



\* Prometheus

\* Grafana

\* CloudWatch



\## Architecture



Developer

↓

GitHub

↓

GitHub Actions

↓

DockerHub / ECR

↓

AWS EKS

↓

Load Balancer

↓

Users



\## Benefits



\* Scalability

\* High Availability

\* Automated Deployment

\* Centralized Monitoring



