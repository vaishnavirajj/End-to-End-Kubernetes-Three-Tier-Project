Welcome to this comprehensive DevOps project! 🚀  
This repository showcases the deployment of a three-tier application (ReactJS, NodeJS, MongoDB) on AWS Elastic Kubernetes Service (EKS) using modern DevOps tools and practices.

## 📚 Table of Contents
- [App Source Code](#app-source-code)
- [Jenkins CI/CD Pipeline](#jenkins-cicd-pipeline)
- [Terraform for Jenkins Setup](#terraform-for-jenkins-setup)
- [Kubernetes Config Files](#kubernetes-config-files)
- [Overview & Tools Used](#overview--tools-used)

---

## 📦 App Source Code
Inside the `Application-Code` folder, you'll find both frontend and backend implementations of the web app. This directory contains the core logic of the application.

## 🔁 Jenkins CI/CD Pipeline
The `Jenkins-Pipeline-Code` folder includes pipeline scripts designed to automate the build, test, and deployment process for this project.

## 🌐 Terraform for Jenkins Setup
`Jenkins-Server-TF` contains infrastructure as code (IaC) scripts built using Terraform to provision the Jenkins server seamlessly on AWS.

## 📂 Kubernetes Config Files
In the `Kubernetes-Manifests-Files` directory, you'll find all Kubernetes resource definitions needed to deploy and manage your app on the EKS cluster.

---

## 🛠️ Overview & Tools Used

### Tech Stack & Tools:
- **Infrastructure:** Terraform, AWS CLI  
- **CI/CD:** Jenkins, Sonarqube, Kubectl  
- **Container Management:** Kubernetes, Helm  
- **Monitoring:** Prometheus, Grafana  
- **GitOps:** ArgoCD

### Project Highlights:
- IAM user creation and AWS resource provisioning using Terraform  
- Jenkins setup with AWS integration for CI/CD  
- EKS cluster setup with Load Balancer for web access  
- Secure image storage via private ECR  
- Monitoring stack integrated using Helm  
- GitOps workflows managed with ArgoCD

> 🔍 This end-to-end setup includes everything from infrastructure creation to deploying a production-ready 3-tier app, integrating automation, monitoring, and DevOps best practices.

---
## 🤝 Contributing
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open a PR or submit an issue.

📬 **Connect with me on [LinkedIn](https://linkedin.com/in/vaishnavirajj)**

---

## 📄 License
This project is available under the [MIT License](LICENSE).

Happy building! 💻🚀
