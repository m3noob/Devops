# Architecture Devops

## Case
As a DevOps Engineer, you are tasked to build, create container, deploy and run this application:
https://github.com/aws-containers/retail-store-sample-app
So, the application could be accessible from the internet or running Well.
Please utilize these tools as much as you can. But you don’t have to utilize all of it. 
1. AWS 
2. GCP 
3. Terraform 
4. Docker 
5. Dockerhub 
6. Kubernetes 
7. Gitlab 
8. Gitlab CI 
9. Jenkins 
Feel free to use your creativity and imagination to finish the task

## Answer
1. Jenkins as CI/CD Server:
   - Install Jenkins on the available server.
   - Configure Jenkins to integrate with code repositories like GitHub or GitLab.
   - Create a Jenkins pipeline for automation of CI/CD steps.
2. AWS EKS (Elastic Kubernetes Service):
   - Create a Kubernetes cluster on AWS EKS.
   - Configure the connection between Jenkins and the EKS cluster. This can be done using the Kubernetes Jenkins plugin or through AWS CLI access on the Jenkins server.
3. Terraform untuk Infrastructure as code (IaC):
   - Install Terraform on the Jenkins machine.
   - Create a Terraform configuration to define the required AWS infrastructure (e.g., VPC, subnet, IAM role, etc.).
   - Use Terraform to automatically provision and manage infrastructure.
4. Docker and Docker Hub:
   - Use Docker to package the application into containers.
   - Create a Dockerfile for each application you want to deploy.
   - Push the generated Docker image to Docker Hub as a repository image.
5. Jenkins Integration with Other Tools:
   - Configure Jenkins to connect with AWS and Docker Hub using the appropriate plugins.
   - Use a Jenkins file to set up CI/CD steps, including steps such as Docker image build, deploy to EKS, and automated tests
