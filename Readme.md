# AWS CI/CD Pipeline

This project demonstrates a **fully automated CI/CD pipeline** using **AWS native services** to deploy a **multi-tier Java application** (Profile App).  
It replaces manual Jenkins-based deployments with a **modern, serverless, AWS-native pipeline** that’s faster, scalable, and cost-efficient.

>  **Goal:** Build a cloud-native CI/CD pipeline using AWS managed services — from commit to deployment — with zero manual steps.

---

### Tech Stack

| Layer | Service | Purpose |
|-------|----------|----------|
| Source Control | Bitbucket | Git repository for application source |
| CI/CD Orchestration | AWS CodePipeline | Automates build and deployment stages |
| Build Tool | AWS CodeBuild | Compiles and packages the Java WAR artifact |
| Deployment | AWS Elastic Beanstalk | Manages app server, scaling, and load balancing |
| Artifact Storage | Amazon S3 | Stores packaged build artifacts |
| Database | Amazon RDS (MySQL) | Backend database |
| DNS + CDN | Route 53 + CloudFront | Domain routing and global content delivery |
| Monitoring | CloudWatch | Centralized logging, metrics, and alarms |


## Project Structure

````
/src                                      # Project Source Directory
├── Architecture.png                      # Cloud Architecture Diagram
├── Guide.pdf                             # Step by Step Deployment Guide
├── Prerequisites.md                      # Prerequisites to Deploy Stack
├── buildspec.yml                         # Build instructions for AWS CodeBuild
├── README.md                             # Project Overview 

````

## 🎥 Demo Video

https://www.loom.com/share/6b5b5bfde8e3438da0c39e63d52cdac3


### **Project Highlights**

This project demonstrates my ability to architect and implement a complete CI/CD pipeline using AWS-native services — integrating Bitbucket for version control, CodeBuild for compilation, and Elastic Beanstalk for deployment. By automating the build-test-deploy workflow end-to-end, I reduced release time by 80%, eliminated operational bottlenecks, and delivered a scalable, secure, and production-ready application infrastructure.



[![Demo](https://img.shields.io/badge/Video-Demo-blue)](https://www.loom.com/share/6b5b5bfde8e3438da0c39e63d52cdac3)


### Author
### Anasieze Ikenna - Cloud Engineer
