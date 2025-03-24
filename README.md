# AWS-DevOps-CI-CD-Project
AWS DevOps CI/CD Project

## 📌 Project Overview  
This project demonstrates a **CI/CD pipeline** using **AWS CodePipeline, CodeBuild, and CodeDeploy**. The goal is to automate the build, test, and deployment process for a sample web application.

## 🛠️ Tech Stack  
- **AWS Services:** CodePipeline, CodeBuild, S3, IAM, EC2 (or EKS)  
- **Infrastructure as Code:** Terraform  
- **Source Control:** GitHub  
- **Scripting:** Shell, YAML  

## 📜 Features  
✅ Continuous Integration & Deployment with AWS CodePipeline  
✅ Automated Build Process using AWS CodeBuild  
✅ Infrastructure Provisioning using Terraform  
✅ Deployment to AWS EC2 (or Kubernetes/EKS)  

## 📂 Project Structure  
/aws-devops-project │── app/ # Application Code │── buildspec.yml # CI/CD Build Configuration │── terraform/ # Infrastructure as Code (Terraform) │── README.md # Project Documentation

bash
Copy
Edit

## 🚀 Getting Started  
1. Clone this repo:  
   ```sh
   git clone https://github.com/richu2000/aws-devops-project.git
Configure AWS credentials:

sh

aws configure
Run Terraform to set up infrastructure:

sh

cd terraform  
terraform init  
terraform apply  
Trigger a CodePipeline build and deploy the application.
