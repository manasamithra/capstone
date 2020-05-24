# capstone project - Hello World

In this project you will apply the skills and knowledge which were developed throughout the Cloud DevOps Nanodegree program. These include:

Working in AWS
Using Jenkins to implement Continuous Integration and Continuous Deployment
Building pipelines
Working with Ansible and CloudFormation to deploy clusters
Building Kubernetes clusters
Building Docker containers in pipelines

About Project:

I created a CI/CD pipeline for a basic website that deploys to a cluster in AWS EKS which is Blue/Green Deployment.

Project Requirement:
To be able to use this CI/CD pipeline you will need to install:

Jenkins
Blue Ocean Plugin in Jenkins
Pipeline-AWS Plugin in Jenkins
Docker
Pip
AWS Cli
Eksctl
Kubectl

The files included are:
* /Capstone_project_Screenshots : Screenshot the result of deploy.
* /container-deploy : CloudFormation Script of Cluster Pipeline file 
* /kubernetes-cluster : Deployment Script of Containers Pipeline file
* Jenkinsfile : Jenkinsfile for Creating Pipeline
* Dockerfile : Dockerfile for building the image 
* green-controller.json : Create a replication controller green pod
* green-service.json : Create the green service
* blue-controller.json : Create a replication controller blue pod
* blue-service.json : Create the blue service
* index.html : Web site Index file.


Run the project:

Please follow to steps of screenshot in Images-of-result-deploy folder.
