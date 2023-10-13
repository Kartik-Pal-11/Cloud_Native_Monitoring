# Cloud-Native-Monitoring-Application
Deploying Flask Monitoring Application in Kubernetes Cluster
![image](./image.png)
Prerequisites
Before you begin, ensure you have the following:

1. An AWS account with appropriate permissions to create EKS clusters and ECS repositories.</br>
2. The AWS CLI installed and configured with valid credentials.</br>
3. Docker installed on your local machine to build the Flask application's Docker image.</br>
4. Basic knowledge of Python, Flask, Kubernetes, and AWS services.</br>

Steps to deploy:
1. Clone the Repository
2. Build the Dockerfile
3. Log in to Amazon ECR
4. Build the Docker image for the Flask monitoring application
5. Push the Docker image to Amazon ECR
  ![image](./ECS.png) 
7. Create Amazon EKS Cluster
 ![image](./EKS.png)
9. Deploy the Flask Monitoring Application to Kubernetes
10. Expose the Application
11. Access the Monitoring Application
![image](./course_at_3138_image.png)

Congratulations! You have successfully deployed a Flask monitoring application in your Amazon EKS Kubernetes cluster, </br>
utilizing Amazon ECS for storing the Docker image. The application allows you to monitor the cluster's health using CPU and Memory utilization gauges.</br>

Reference:</br>
Cloud Champ</br>
Source : https://www.youtube.com/watch?v=kBWCsHEcWnc&pp=ygUjY2xvdWQgbmF0aXZlIG1vbml0b3JpbmcgYXBwbGljYXRpb24%3D
