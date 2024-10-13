# -Performing-blue-green-deployments-with-CI-CD-pipelines-and-Amazon-Elastic-Container-Service
Project Overview
In this project, you will use AWS DevOps tools to build Docker container images and store them in Amazon Elastic Container Registry (Amazon ECR). You will implement blue/green deployments of a containerized web application into an Amazon Elastic Container Service (Amazon ECS) cluster managed by AWS Fargate. Additionally, you will configure a comprehensive continuous deployment (CD) pipeline using AWS CodeBuild, Amazon ECR, and AWS CodeDeploy to build and store the container image and then perform a blue/green deployment.

Blue/green deployments minimize interruptions to the customer experience and provide rapid rollback capabilities. Automating a blue/green deployment model increases the delivery speed of a DevOps team by supporting the concepts of Continuous Integration (CI) and Continuous Deployment (CD).

Project Resources
To help you get started, the following resources will be provided:

Sample code for your web application, including a Dockerfile used to build the container image.
Specification files for deployment.
A cluster to deploy your container images into.
Supporting AWS infrastructure resources needed to implement this solution using CI/CD pipelines, such as a VPC, an Internet Gateway, subnets, IAM roles, an Application Load Balancer, AWS CodeCommit repositories, and more.
Objectives
By the end of this project, you will be able to:

Build custom container images using AWS CodeBuild and store them in Amazon ECR.
Set up a CI/CD pipeline to automate the creation of application container images using AWS CodePipeline.
Host and run a containerized web application using Amazon ECS and AWS Fargate.
Configure AWS CodeDeploy to perform a blue/green deployment.
Set up a CI/CD process to automate the build and deployment of a containerized web application.
