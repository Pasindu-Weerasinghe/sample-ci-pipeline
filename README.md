# Basic CI Pipeline Setup with Jenkins on AWS Lightsail

This repository contains a step-by-step guide to create a basic CI pipeline using Jenkins on AWS Lightsail.

## Step 1: Set Up Your Project Repository on GitHub

1. **Create AWS Lightsail**
   - Create an AWS Lightsail instance.

2. **Install Jenkins**
   - Install Jenkins on the AWS Lightsail instance.

3. **Create GitHub Repository**
   - Create a new repository on GitHub for your project.

4. **Clone the Repository Locally**
   - Clone the GitHub repository to your local machine:
     ```bash
     git clone https://github.com/Pasindu-Weerasinghe/sample-ci-pipeline.git
     ```

5. **Add a Simple Project**
   - Add a simple project to your repository.

6. **Commit and Push the Changes**
   - Commit your changes and push them to GitHub:
     ```bash
     git add .
     git commit -m "Initial commit"
     git push origin main
     ```

## Step 2: Configure Jenkins

1. **Create a New Jenkins Job**
   - Access Jenkins on your AWS Lightsail instance and create a new Jenkins job.

2. **Configure the Pipeline**
   - Configure the pipeline for the Jenkins job.

## Step 3: Create a Jenkinsfile

1. **Add a Jenkinsfile to Repository**
   - Create a `Jenkinsfile` in the root directory of your repository.

## Step 4: Run the Pipeline

1. **Trigger the Build**
   - Trigger the build in Jenkins.

2. **Check the Build Status**
   - Check the build status in Jenkins.

To set up a webhook to automatically trigger your Jenkins pipeline when changes are pushed to this GitHub repository

## Step 1: Configure GitHub Webhook

1. **Navigate to Your GitHub Repository**
   - Navigate to your GitHub repository.

2. **Add a New Webhook**
   - Add a new webhook to your GitHub repository.

## Step 2: Configure Jenkins to Receive GitHub Webhooks

1. **Configure Jenkins Job to Use GitHub Webhooks**
   - Configure Jenkins job to use GitHub webhooks.

## Step 3: Test the Webhook

1. **Push a Change to Your Repository**
   - Push a change to your repository.

2. **Check Jenkins**
   - Check Jenkins for the triggered build.