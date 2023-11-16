## Overview

Welcome to our documentation designed to guide DevOps beginners through their exciting first steps in the world of 
modern application deployment. In this guide, we will explore the use of essential technologies such as Docker, Docker Hub,
Minikube, and GitHub workflows to simplify the process of creating, managing, and deploying applications.


### 1. Docker and Docker Hub:

Docker simplifies the software development lifecycle by offering a standardized way to package, distribute, and deploy
applications. Developers can create Docker images containing their applications and share these images, along with all dependencies,
ensuring a seamless transition from development to testing and production. 

Docker Hub hosts a vast collection of public images for popular software, libraries, and frameworks, making it a valuable resource for
the Docker community.Developers can use Docker Hub to publish their own images, share them with others, or use images created by the community.

#### What You Will Learn:

- Learn how to create containers with Docker to encapsulate your applications.
- Explore Docker Hub as a platform to store, share, and manage your container images.
- Learn to build Docker images and publish them to Docker Hub.

### 2. Minikube:

Minikube is a tool designed to enable developers to run Kubernetes clusters locally on their machines. 
Kubernetes is a powerful container orchestration platform that helps manage, deploy, and scale containerized applications.
Minikube simplifies the process of setting up a local, single-node Kubernetes cluster for development and testing purposes.

#### What You Will Learn:

- Understand the basics of Kubernetes, a container orchestration platform.
- Use Minikube to create a local Kubernetes cluster on your development machine.
- Deploy applications to the Minikube cluster and grasp the fundamentals of container orchestration.

### 3. GitHub Workflow:

GitHub provides a central hub for hosting and sharing code, facilitating collaboration among distributed development teams.
It offers features such as pull requests, issues, and project management tools, enhancing the overall development workflow.

CI/CD workflow using Git and GitHub, developers work on feature branches and create pull requests to propose changes.
Automated CI processes, triggered by these pull requests, run tests to validate code changes. Once tests pass, the changes are
merged into the main branch, triggering automated CD processes for deployment.

#### What You Will Learn:

- Set up GitHub workflows to automate the build and deployment process.
- Explore GitHub Actions to build and push Docker images on code changes.
- Learn to integrate CI/CD pipelines into your development workflow.

## Why DevOps:
The DevOps philosophy aims to bridge the gap between development and operations, fostering collaboration and automation for 
faster and more reliable deployments. By mastering these technologies, you'll be better equipped to manage the entire lifecycle 
of your applications efficiently and in a modern way.

Start your DevOps journey now and transform the way you develop and deploy applications! Follow our step-by-step guide 
to explore these key technologies and make your DevOps experience a rewarding adventure.

## Configs

##### Docker hub

- Log in to docker by executing this command: docker login.
- Add the user name and access token that you can generate [here](https://hub.docker.com/settings/security).

- 
##### Github

- Add two variables on {repo}-> settings -> secrets -> actions to push the new image to docker hub after each git pipeline run.

##### Minikube

- Install minikube in your machine and make sure the installation was successful.
-  Create a namespace named 'project' or a name of your choice.
