# Next.js CI/CD Pipeline Showcase

This project demonstrates a Continuous Integration (CI) and Continuous Deployment (CD) pipeline for a Next.js application using GitHub Actions and AWS CodePipeline.

## Overview

This project serves as a showcase for setting up automated workflows for building, testing, and deploying Next.js applications using modern CI/CD practices.

### Features

- **GitHub Actions Workflow**:
  - Automatically triggers on every push to the `main` branch.
  - Builds the Next.js application.
  - Runs tests to ensure code quality.
  - Deploys the application to AWS S3 bucket.

- **AWS CodePipeline**:
  - Orchestrates the CI/CD process.
  - Integrates with GitHub to fetch source code.
  - Manages the stages of Build, Test, and Deploy.
  - Utilizes AWS services like AWS CodeBuild and AWS S3 for building and deployment.

## Setup

Follow these steps to set up the CI/CD pipeline in your own project:

1. **Clone Repository**: 
   ```sh
   git clone https://github.com/your-username/your-nextjs-app.git
```
