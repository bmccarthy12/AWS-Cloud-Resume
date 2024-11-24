# Cloud Resume Challenge

The **Cloud Resume Challenge** is a hands-on project designed to integrate core AWS services and demonstrate skills in full-stack development, serverless architecture, and CI/CD workflows. This project bridges the gap between theoretical knowledge and practical application in cloud technologies, showcasing expertise in building scalable, automated, and secure solutions.

## Overview

The challenge involves creating a static resume website with dynamic backend features. It emphasizes skills in **frontend development**, **backend integration**, **cloud infrastructure management**, and **automation**. Below is a summary of the steps and components completed:

---

## Project Components

### 1. **Frontend Development**
- Developed the resume using **HTML**, **CSS**, and **JavaScript** for structure, styling, and interactivity.
- Hosted the static website on an **Amazon S3 bucket**, configured for private access with a **CloudFront distribution** for secure content delivery via HTTPS.
- Registered a custom domain using **Route 53** and integrated it with the CloudFront distribution for a professional web presence.

---

### 2. **Backend Development**
- Built a **visitor counter** feature using AWS serverless technologies:
    - **DynamoDB**: Stores and updates visitor counts in a NoSQL table.
    - **API Gateway**: Serves as the endpoint for communication between the frontend and backend.
    - **AWS Lambda**: Executes the business logic for updating and retrieving visitor counts. The Lambda function was written in **Python**.
- JavaScript was integrated into the frontend to interact with the API and dynamically update the visitor count.

---

### 3. **Automation and CI/CD**
- Implemented **GitHub Actions** for continuous integration and deployment:
    - Frontend changes are automatically synced to the S3 bucket.
    - Backend changes trigger updates to Lambda functions and API configurations.
- Automated processes include:
    - CloudFront cache invalidation for immediate content updates.
    - Deployment pipelines for testing and production environments.

---

## Skills Demonstrated
- **AWS Services**: S3, CloudFront, Route 53, DynamoDB, API Gateway, Lambda
- **Programming**: HTML, CSS, JavaScript, Python
- **Serverless Architecture**: Hands-on experience with serverless technologies for scalability and cost efficiency.
- **CI/CD Pipelines**: Automated deployment workflows using GitHub Actions.
- **Security**: Configured IAM roles and bucket policies for secure operations.

## Project Benefits
- Improved understanding of cloud services, serverless design patterns, and infrastructure automation.
- Hands-on experience in integrating frontend and backend technologies.
- Enhanced proficiency in Python, JavaScript, and AWS tools.
[See website here](https://www.genome.gov/)
