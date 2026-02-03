# CI CD Pipeline with GitHub Actions and AWS

## Overview
This repository contains a production oriented CI CD pipeline built with GitHub Actions and AWS.  
The pipeline automates build, testing, security checks, and Docker image publishing for a Java application.

It is designed to reflect how real teams safely release code to production.

## What the Pipeline Does
- Triggers on push, pull request, manual, and scheduled runs
- Builds the application using Maven and packages a WAR file
- Runs tests and static analysis on the main branch
- Performs security scanning using Trivy
- Enforces job dependencies so only verified code is released
- Builds and pushes Docker images to Amazon ECR from main only
- Uses GitHub secrets and environment protection for AWS access

## Tools Used
- GitHub Actions
- Maven
- Docker
- Trivy
- AWS IAM
- Amazon ECR

## Key Takeaway
This pipeline focuses on control, security, and repeatability rather than just passing builds.
