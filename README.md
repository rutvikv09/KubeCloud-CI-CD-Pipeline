# Kubernetes CI/CD Pipeline & GKE Deployment 🚀

## Overview

This project involves building a robust, cloud-native CI/CD pipeline and deploying a workload to Google Kubernetes Engine (GKE). It showcases expertise in containerization, CI/CD pipelines, and Kubernetes concepts, with a focus on practical application in a real-world cloud environment.

## Learning Outcomes 🎓

- Mastery of containerizing applications using Docker.
- Proficiency in building and managing code deployment pipelines with GCP tools.
- Experience in using Kubernetes and GCP tools to create clusters and deploy applications.
- Skills in managing persistent volumes in GKE and handling data operations.
- Competence in using Kubernetes tools, like `kubectl`, for monitoring and troubleshooting.
- Understanding of application update strategies and REST API development.

## Architecture Diagram 🏗️

![K8s](https://github.com/user-attachments/assets/e2d635f5-e30b-4ac1-abe2-7d09d8c69587)


## Features 📋

### Container 1

- Deployed as a service in GKE.
- Accesses and interacts with a persistent volume.
- Implements a `/store-file` API to store files in persistent storage.
- Implements a `/calculate` API to compute the sum of products from a file.

### Container 2

- Accesses the persistent volume.
- Calculates the total of a specific product from a file.
- Returns JSON responses based on file content and potential errors.

### CI/CD Pipeline 🚧

- Utilizes GCP Cloud Source Repository for code management.
- Employs GCP Cloud Build to automate CI/CD pipelines.
- Ensures that the GKE cluster is updated with new code commits seamlessly.

### Terraform Script 📜

- Develops a Terraform script for creating and configuring the GKE cluster.
- Optimizes the cluster configuration to manage costs effectively.

### YAML Configuration 📄

- Defines a YAML file for deploying applications and services to GKE.
- Configures persistent volume mounting and accessibility.

## Implementation Details 📝

### Video Demonstration 🎥

- Shows the creation of the GKE cluster using Terraform.
- Highlights the CI/CD pipeline setup and deployment process.
- Demonstrates API functionality by making requests and validating responses.

### Code Repository 💻

- Code and YAML files are organized in a folder named `K8s` within this repository.
- All files are committed and maintained for version control.

## Achievements 🏆

- Successfully implemented a cloud-native CI/CD pipeline with GKE.
- Deployed and managed containerized applications with persistent data storage.
- Automated deployment workflows and ensured continuous integration.

## 🙋‍♂️ Contact

- For any questions or feedback, please reach out to vaghanirutvik777@example.com.

**Thank you for checking out this project!** 🍀
