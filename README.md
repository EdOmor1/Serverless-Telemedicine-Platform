# Serverless-Telemedicine-Platform

# Overview
The Serverless Telemedicine Platform project aims to build a scalable and secure telemedicine platform on AWS using serverless technologies. It provides a backend API for telemedicine functionalities and a frontend web application for users to interact with.

# Components
# Backend
- Lambda Function: Handles telemedicine functionalities like appointment scheduling, video consultations, etc.
- API Gateway: Exposes HTTP endpoints for frontend communication with the backend.

# Frontend
- Web Application: Provides a user-friendly interface for patients and doctors to interact with the telemedicine platform.

# Infrastructure as Code
- CloudFormation Templates: Defines AWS resources such as Lambda functions, API Gateway, Cognito user pool, and DynamoDB tables in a declarative manner.

# Deployment Script
- deploy.sh: Automates the deployment process by executing CloudFormation templates and deploying AWS resources.

# Usage
- Run the deploy.sh script to deploy AWS resources defined in CloudFormation templates.
- Access the frontend web application hosted on AWS.
- Users (patients and doctors) can sign up/login, schedule appointments, and conduct video consultations through the platform.

# Prerequisites
- AWS CLI installed and configured with appropriate IAM permissions.
- Basic knowledge of AWS services such as Lambda, API Gateway, Cognito, DynamoDB, and CloudFormation.
- HTML, CSS, and JavaScript skills for frontend customization and development.

# Contributing
- Contributions are welcome! Please feel free to submit issues, pull requests, or suggestions.
