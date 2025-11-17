📦 Ecommerce_Aniket

A complete Ecommerce Web Application built using Java, Maven, Docker, Jenkins, Nexus, SonarQube, and Trivy — fully automated with a production-grade CI/CD pipeline.

🏆 Project Badges








🚀 Project Overview

This repository showcases a complete CI/CD implementation for a Java-based ecommerce application.
The pipeline automates:

Build

Test

Code Quality Analysis

Vulnerability Scanning

Artifact Deployment

Docker Image Build & Push

Application Deployment on AWS EC2

Perfect for DevOps portfolio, LinkedIn, resume, interviews or demo projects.

🏗️ Architecture Diagram

📌 To make this work:
Create a folder named assets/ in the root of your repo and upload your architecture diagram as:

assets/architecture.png

🔄 CI/CD Pipeline Diagram

📌 Upload your pipeline diagram to:

assets/pipeline.png

📸 CI/CD Screenshots

Create a folder named screenshots/ in your repo and upload your images:

screenshots/jenkins_pipeline.png
screenshots/sonarqube.png
screenshots/nexus.png
screenshots/docker_push.png
screenshots/ec2.png
screenshots/app_running.png


Then the images will display correctly:

✅ Jenkins Pipeline

✅ SonarQube Analysis

✅ Nexus Repository

✅ Docker Push Logs

✅ EC2 Deployment

✅ Live Running App

🛠️ Tech Stack
Application Technologies

Java

Maven

JSP/Servlet

WAR Deployment

DevOps Tools

Jenkins

SonarQube

Nexus Repository Manager

Docker

Docker Hub

Trivy Security Scanner

AWS EC2

Git & GitHub

📁 Repository Structure
Ecommerce_Aniket/
│── src/
│── Dockerfile
│── pom.xml
│── Jenkinsfile
│── README.md
│── assets/
│   ├── architecture.png
│   └── pipeline.png
│── screenshots/
│   ├── jenkins_pipeline.png
│   ├── sonarqube.png
│   ├── nexus.png
│   ├── docker_push.png
│   ├── ec2.png
│   └── app_running.png

🔧 Local Build Instructions
Compile
mvn compile

Package
mvn package -DskipTests=true

Run Using Docker
docker build -t aniketgh5/ecommerce:latest .
docker run -p 8080:8080 aniketgh5/ecommerce:latest

🔗 Important Links
👨‍💻 Developer – Aniket Ghosh

🔗 LinkedIn: https://www.linkedin.com/in/aniketghosh6/

📧 Email: checkaniket@gmail.com

📝 License

Open-source project — free to use for learning & portfolio.

⭐ Support

If you find this project helpful, please consider giving it a ⭐ on GitHub!