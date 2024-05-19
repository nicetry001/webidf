
# https://webidp.ar-w.info
# Web Identity Federation using Cognito and Google

## Overview

This repository contains a simple serverless application that demonstrates the implementation of Web Identity Federation using Amazon Cognito and Google as the Identity Provider (IDP). The application utilizes various AWS services including S3 for front-end application hosting, Cognito for authentication and authorization, IAM Roles for swapping Google Tokens for AWS credentials, and presigned URLs for accessing private S3 bucket resources securely.

## Architecture

![webidf](https://github.com/nicetry001/webidf/assets/85026477/2906b97d-7028-4add-8c99-26459aaf0644)


## Technologies Used

- **S3**: Used for hosting the front-end application.
- **Google API Project**: Serves as the Identity Provider for user authentication.
- **Cognito**: Manages user authentication and authorization.
- **IAM Roles**: Enables the swapping of Google Tokens for AWS credentials.
- **Presigned URLs**: Used to securely access private S3 bucket resources.
- **CloudFront**: Content Delivery Network (CDN) for caching and delivering content globally.
- **Certificate Manager**: Manages SSL/TLS certificates for securing connections.
- **Route 53**: DNS service for routing traffic to resources.
- **GitHub**: Version control and repository hosting platform.
- **GitHub Actions**: CI/CD tool for automating workflows.
