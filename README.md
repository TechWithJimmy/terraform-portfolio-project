# Website Deployment Project Portfolio

This project showcases the deployment of a Next.js application utilizing AWS services like S3, CloudFront, DynamoDB, and bucket policies. The infrastructure is provisioned and managed with Terraform.

# Table of Contents

1. Architecture
2. Technologies Used
3. Setup and Deployment
4. Prerequisites
5. Installation
6. Deploying the Infrastructure


# The infrastructure for this project is built using the following AWS services:

Amazon S3: Used to store static files of the Next.js application.
Amazon CloudFront: Provides a CDN for the static files, enhancing the performance and security of the application.
Amazon DynamoDB: Used for storing data related to the application.
Terraform: Used to define and provision the cloud infrastructure.
Bucket Policies: Used to control access to the S3 buckets.
The architecture ensures that the application is scalable, secure, and highly available.

# Technologies Used

Next.js: A React framework for building server-side rendering and static web applications.
AWS S3: Object storage service that offers industry-leading scalability, data availability, security, and performance.
AWS CloudFront: A fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally.
AWS DynamoDB: A key-value and document database that delivers single-digit millisecond performance at any scale.
Terraform: An open-source infrastructure as code software tool that provides a consistent CLI workflow to manage hundreds of cloud services.

# Setup and Deployment

Prerequisites
Ensure you have the following installed:

Terraform
AWS CLI
Node.js and npm

# Installation

Clone the repository:
git clone https://github.com/yourusername/nextjs-portfolio.git
cd nextjs-portfolio

# Install the dependencies:

npm install

# Deploying the Infrastructure

Configure AWS CLI with your credentials:
aws configure

Initialize Terraform:
terraform init

Apply the Terraform configuration:
terraform apply
